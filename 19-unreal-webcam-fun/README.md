# unreal webcam fun

## description


### Learnings
- clear: both;

- navigator.mediaDevices.getUserMedia({ video: true, audio: false })  ==> allow camera access / allow camera stream
        .then(localMediaStream => {
            console.log(localMediaStream);
             video.srcObject = localMediaStream;
            video.play();  
        }).catch(err => {
            console.error('oh no');
        });
- video.videoWidth;
- video.videoHeight;
- send image from video to canvas 
    - setInterval(() => {
        ctx.drawImage(video, 0, 0, width, height);  // top left width height
    }, 16);

-  canvas.toDataURL('image/jpeg');  // get image from vanvas
- video.addEventListener('canplay', paintToCanvas);

<audio class="snap" src="snap.mp3" hidden></audio>

- snap.play(); 

-  ctx.getImageData(0, 0, width, height); // get image data

-  ctx.putImageData(pixels, 0, 0); // set data to image 

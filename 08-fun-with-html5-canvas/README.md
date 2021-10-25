# canvas

## description


### Learnings
-  <canvas id="draw" width="800" height="800"></canvas> should take width and height
- ctx = canvas.getContext('2d');
    - canvas.height = window.innerHeight;
    - canvas.width = window.innerWidth;
    - ctx.strokeStyle color
    - ctx.lineJoin = 'round';
    - ctx.lineCap = 'round';
    - let isDrawing = false;
    - ctx.globalCompositeOperation = 'multiply';  => shape of coloring
    - ctx.strokeStyle = `hsl(${hue},100% , 50%)`;  => change color to gradient 
    - start drwaing 
        -  ctx.beginPath();
            //start
            ctx.moveTo(lastX, lastY);
            //end
            ctx.lineTo(e.offsetX, e.offsetY);
            ctx.stroke();
    - 
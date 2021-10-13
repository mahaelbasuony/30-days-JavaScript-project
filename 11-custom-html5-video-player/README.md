# custom html5 video player

## description


### Learnings


- in css
    -  background: linear-gradient(135deg, #7c1599 0%, #921099 48%, #7e4ae8 100%);  //https://www.w3schools.com/css/css3_gradients.asp
    - .player:fullscreen{} - .player:-webkit-full-screen{}
    - cursor: ew-resize;
    -  The flex-basis property specifies the initial length of a flexible item.
        - flex : 10;
        - flex-basis:100%;
    - -webkit-appearance: none;
    - ::-webkit-slider-runnable-track - ::-moz-range-track 
    - ::-webkit-slider-thumb 
- in js
    - video properties
        - video.play();
        - video.pause();
        - video.paused
        - this.dataset.data-name
        - video.currentTime
        - range.name
        - range.value
        -  progressBar.style.flexBasis
        - video.duration
        - e.offsetX 
        - progress.offsetWidth
    -  const method = video.paused ? 'play' : 'pause';  video[method](); // make pause and play like an array


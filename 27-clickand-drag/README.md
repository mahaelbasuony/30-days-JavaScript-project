# click and drag to scroll

## description


### Learnings
- .item:nth-child(9n+1) {
    background: dodgerblue;
}  ====> give this bg color to number 1 and 9

- .item:nth-child(even){}

- .item:nth-child(odd){}
- overflow-x: scroll;
    overflow-y: hidden;
    white-space: nowrap;

-  user-select: none; // no select for copy 
-  will-change: transform; // tell the browser how it change 
- perspective: 500px; // Give a 3D-positioned for element 
- cursor: grabbing; // hand

- startX = e.pageX - slider.offsetLeft;
-  e.preventDefault(); // not allow to select any items 


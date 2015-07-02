# Panning-Zooming-Canvas-Demos

A series of demos that shows how to display an image on a html5 canvas, pan around, zoom in and out

### Demo 1
Introduction to HTML5 canvas. How to initialize a canvas object and draw a colored rectangle.

### Demo 2
How to intialize an image object and draw it inside of the canvas

### Demo 3
How to calculate the scaling of an image given a predefined width and draw it to the canvas

### Demo 4
Initialize a bunch of canvas events: clicking (mousedown), dragging (mousemove), letting go (mouseup) and write a simple log of the events.

### Demo 5
Grab the coordinates of mousedown, initialize the drag event and update the distanced moved from dragging. Update the canvas image based on distanced moved/dragged.

### Demo 6
Keep track of how far the image moved based on previous drag events instead of resetting the image position to 0,0 every time.

### Demo 7
Incorporate jQuery to quickly handle/access button events for new Zoom in and Zoom out options. Use a basic 2x zoom scale and multiply the size by 2 when zooming in. Divide by 2 when zooming out. Redraw the canvas with new sizes for each zoomin/zoomout event.

### Demo 8
All zoom in/zoom out events were initially being draw to 0,0 for the upper left coordinate. Zoom in/out to the center of image instead of the top left. 


### Demo 9
Since we're calculating the center frequently, create a method that can be used throughout instead of calculating it every event. Also set the initial image display to be centered.
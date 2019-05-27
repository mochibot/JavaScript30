Things learned
- HTML5 canvas: container for graphics; must use JavaScript to actually draw graphics
- To get canvas' 2D rendering context, call getContext() on <canvas> element and use '2d' as argument
- methods:
  .beginPath()  - create a new path
  .moveTo()     - move starting point to new (x,y) coordinates
  .lineTo()     - connect the last point to the specified (x, y) cooredinates with a straight line
  .stroke()     - strokes the current sub-paths with current stroke style


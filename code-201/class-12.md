# Canvas
canvas are better to display data than tables
we start with chart.js and plagin the HTML canvas element from the HTML file to draw a graph like (bar charts, line charts, pie charts and so on..)
```
example
<canvas> element 
<canvas id="buyers" width="600" height="400"></canvas>
```
Drawing paths
steps to make a shape using paths
- `beginPath()` : creates a new path
- path methods: sets a differnt paths for objects
-  `closePath()` : adds a straight line to the path and starts a sub-path
- `strokePath()`: draws the shape by stroking its outline
- `fill()`: draws a solid shape by filling the path's content area.



Drawing Text

fillText(text, x, y [, maxWidth])

- Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth])

Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

the default font-value is 10px sans-serif.

- text alignment settings are `start, end,left, right, center`. the defoult value is `start`.
- text baseline alignment settings `top, hanging, middle, alphabetic, ideographic,bottom`. the default is `alphabetic`.
- direction-value are `ltr,rtl,inherit`. the defoult is `inherit`.

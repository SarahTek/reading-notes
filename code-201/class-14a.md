# Transforms
- allows you to move, rotate, scale, transition, and skew an element. 

- Two-dimensional transforms
 - 2D transform works on the x and y axes or vertical and horizontal axes.
- Three-dimensional transforms also works in x and Y axes as well as Z axis.it helps define length , width and depth of an element.

2D Rotate 
- using a positve value like from 0 to 360 degrees will rotate and element clockwise and using negative will rotate Counterclockwise.

example:
```
.div-1 {
  transform: rotate(20deg);
}
.div-2 {
  transform: rotate(-55deg);
}
.div-3 {
  transform: scale(1.25);
}
.div-4 {
  transform: translate(-10px, 25%);
}
```
- use a scale value to change the size of an element
- to change the height and width of an element use scaleX and scaleY values
- to set both the x and y axis values at once declare the X axis folloed by comma and the Y axis value.
```
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```
## Transitions and Animations
With CSS3 transitions you can change the behaviour and apperance of an element, such as when it is hovered over, focused on, active, or targeted.

## some examples of the Simple CSS3 Transitions
- fade in 
- Change color
- Grow and shrink
- rotate element
- square to circle
- 3D shadow
- swing
- inset border

website: 
- [CSS3 Transitions](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/)
- [CSS3 Transforms, Transitions and Animations](https://learn.shayhowe.com/advanced-html-css/)

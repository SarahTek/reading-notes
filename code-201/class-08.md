# More CSS Layout
# Layouts
## **Building Blocks**

`block-level` elements starts in a new line and acts as the main building blocks of any layout.

`inline box` flows between surrounding text.


## Position element
`normal flow`: a block-level element appear in a new line 

`relative positioning`:exactlyu does as a static postioning but it allows you to  shifts an element from the position it would be in normal flow moving it from right, left ,top,bottom. 

`absolute positioning`: takes the document out of the document flow.

`fixed positioning`:fixed positioning are fixed relative , even if the page is scrolled, they stay in exactly the same position inside the browser window.

`floating positioning`: allows you to postion an element out of normal flow. you can position it right, left of a containing box.

`postion:static`: is a default way in which browser treat HTML elements


`Z-index`:used to control an element that sits on top of an element. use z-idex property and its value is a number.

### Clearing floats

`clear`: prperty allows you to say that no element should touch the left or right side of s box.

`clear`{
  `clear: right`;(right-hand side of the box will not touch an element)
  `clear: left`;(left-hand side of the box eill not touch an element)
  `clear: both`;(neither left nor right side will touch an element)
  `clear: none`;(elements can touch either side)
}

`fixed layout` used pixels tp specify the width of esch box.

`liquid layout` uses percentage.

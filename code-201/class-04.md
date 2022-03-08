# HTML
## **LINKS**
* links are created using < a></ a> tags , href is an attribute(specifies which page to link).
example: 
```
<a href="https://www.google.com">link text</a>
```
* Relative urls are used to when liking a page within your own website.

## **Email Links**
 * To create email link you use a < a> and href, mailto: followed by  email address you want the email to be sent
```
<a href="mailto:sarah@gmail.com>sarah's email</a>
```
## **Target**

if you want a link to open in a new window use target attribute and the value should be _blank.
```
<a href="www.google.com" target="_blank">google</a>
```

```
 linking to a specific part of the same page`

<a href="#movies">movie list</a>

```

```
linking to a specific part of the another page

<a href="https.www.google.com/#movies">movie list</a>
```

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

- `clear`: prperty allows you to say that no element should touch the left or right side of s box.
  - `clear: right`;(right-hand side of the box will not touch an element)
  - `clear: left`;(left-hand side of the box eill not touch an element)
  - `clear: both`;(neither left nor right side will touch an element)
  - `clear: none`;(elements can touch either side)

- `fixed layout` used pixels tp specify the width of esch box.

- `liquid layout` uses percentage.


# Javascript


## what is function?
Functions let you group a series of statements together  to perform a specific.
code block is consisted of one or more statements contained with curly braces.parameters
return value

## Declaring a Function

To declare a function you need to give the function a name and followed by a statement inside a curly braces{}.
``` 
function yourName {
  documnent.write('Name');
}

```
## Calling a Function

to run the code you use the function name followed by ().in this case:
```
yourName();
```

## Declaring a function using a parameters
```
function areaSize(width,height){
  return width * height;
}
```
`width and height` are parameters.
```
arguments as values
areasize(3,5);

arguments as variables
areaWidth=3
areaHeight=5
areaSize(areaWidth,areaHeight);
```

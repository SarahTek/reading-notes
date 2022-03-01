# HTML
## Images
- To add an image you should you use the image element.
```
<img src="url" alt="text description">
<>
```

- height: specicies the height of the image in pixels.
- width: specicies the width of the image in pixels. 

`< align>` is used to indicate how parts of the page should flow around the image.

Three rules for creating images
- saving image in the right format
- saving image at the right size
- measuring image in pixels
  - use pixels only when sizinf an image.
  `< figure>` is used to contain one or more images together.
  `< figcaption>` used to add caption to an image.
 
 # Color
 color specifies the color of text inside an element.
 ```
 RGB values: red, blue, green are expressed as a number from 0 - 255.
 HEX codes: represents values in hexadecimal code.
 COLOR names: we name colors .
 ``` 
 - `background-color`: speciefies the background-color.
 - contrast: 
    - high contrast
    - low contast
    - medium contrast

`CSS3 `introduces an extra value for RGB color to indicate opacity, it is known as RGBA.

 - `opacity rgba`: sets the opacity level of an element. the level of opacity describes the transparency level of an element and its child. the value is a number between 0.0 and 1.0 . 0.5 is 50% opacity and 0.15 is 15% opacity. it add the opacity value in rgb(a) colors.
 example:`{ back-ground-color: rgba(0,0,0,);
          opacity: 0.5;}`

 - `HSLA colors`
   - `Hue`: is a colloquial idea of color. hue is a color circle.The value is from 0 to 360.
   - `Saturation`: is the amount of gray in a color.
   - `Lightness` : is the amout of whote or black in a color.
   - `Alpha` represents transparency
   - brightness only adds `black`. And lightness offer both `black and white`.




  # Text
Specifing Typefaces

`font-family`: is a set of fonts that have a common a design. The font-family property can hold several font names

`font-size`: sets the size of the font.we use pixels ,percdentages and ems.

`@font-face`: allows you use to use a font.

`font-weight`: is the “value” placed on your font that will determine how bold or light your text will appear

`font-style`:refers to the size, weight and color of a text. three vales of a font-style property(normal, italic and oblique)

`text-transform`: changes the case of a text to uppercase , lowercase, and capitalize.

`text-decoration`:  sets the appearance of decorative lines on text. we use (underline, overline, line-through,blink, none)

 `line-height`: sets the height of the entire text.

`letter-spacing`: control the space between each letter

`word-spacing`: contrls the gap between words.

`text-align`: controls the alignment of a text using (left , right, center, justify).

`vertical-align`:is an inline element's box inside its containing line box.

`text-indent`: specifies how much horizontal space text should be moved before the beginning of the first line of the text content of an element.

`text-shadow`: creates a shadow.

`:first-letter`:applies styles to the first letter of the text inside an element.

`first-line`: applies styles to the first line of the text inside an element. 

`:link`: apples style to a link that have not been visited.

`:visited`applies a style for a link that have been clicked.

`:hover`: applies changes to the apperance when user place their cursor over them. 

`:active`: is used to select and style the active link

`:focus`: applies when an element has focus.

Attribute selectors

- existence `[]`
- Equality `[=]`
- Space `[~=]`
- prefix `[^=]`
- substring `[*=]`
- suffix `[$=]`

# FORMS
- `forms` controls th live inside the < form>
- `action` is the url of the page.
- `< input>` element is used to determine several different form controls.
`< name>` creates the name of the input.

Drop down list box
- `< select>` button allows user to select one option from the drop down list.
`< option>` specify the option that users can select.
`type=file` creates a box that looks like a text input follwed by browse button.
`type=image` used if you want to use image for a submit button.
# Lists , Tables and Forms
- `list-style position` used for the marked should inside or outside of the box.
- `list-style` allows you to express the marker's style.
- `border spacing` controls the distance between borders
- `border collapse` collapse in to a single border

# Events
UI Events
- `load` web page has finished loading
- `unload` web page is unloading.
- `error` browser incounter javascript error
- `resize` browser window has been resized
- `scroll` user has scrolled up and down

Keyboards Events
- `keydown` user presses a key
- `keyup` user releases a key
- `keypress` character is being inserted

Mouse Events 
- `click` presses and releases a button over the sane element 
mouse down 

## How Events trigger Javascript code 
1. select element 
2. specify event 
3. call code

## Traditional DOMEvent Handlers
- you can only attach one function to each event Handler
```
element.submit = functionName;
```
## Event Listeners
- they can deal with morethan one function at a time.

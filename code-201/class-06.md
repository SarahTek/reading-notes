# objects
* what is an object?

objects are a set of variables and functions to create something eou can recognize in a real world

variable is part of an object, it is also called Property. it itells about the object
a function is also part of an objects it is also called a method. it represents the task that are associated with the object.

# Document Object Model (DOM)

The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web.
there are four types of DOM.
## Four types of DOM
- The Document Node
- The Element Node
- The Attribute Node
- The Text Node
working with the DOM involves 2 steps
##  Access the element
- `getElementById()` uses the id attribute
- `querySelector()` uses css selector and return the first match
- `querySelectorAll()` uses css selector and return all matching elements
- `getElementByClassName()` selects all the class attribute
- `getElementsByTagName()` selects all element with a specific tag name
- `parentNode` selectsthe parent of the current element node
- `prevoiusSibiling/nextSibiling` selects previous or next sibiling
- `firstChild/lastChild` selects the first or last child of the current element
## looping through a node list 
```
for (var i = 0 i < hotItems.length; i++){
  hotItems[i].classname = 'cool';
}
```
## work with those element
- `nodeValue` access or update content in the text node.
- `innerHTML` allows access to child element and text content
- `textContent` allows access to text content
- `createElement` creates new node
- `appendChild` addes node to a tree
- `removeChild` removes node from a tree
- `hasAttribute` checks an attribute if it exists
- `getAttribute` gets the value
- `setAttribute` updates the value
- `removeAttribute`  remove an attribute
- methods that find elements in DOM tree are called **DOM queries.**
- A **nodelist** is a collection of element nodes.

### Looping through a nodelist example
```
var hotItems = document.querySelectorsAll('li.hot');
if (hotItems.length > 0){
  for (var i = 0; i <hotItems.length; i++){
    hotItems[i].className = 'cool';
      }
}
```

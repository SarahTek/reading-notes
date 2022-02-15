# HTML

## HEADINGS
HTML has six level of Headings.
```
h1 is used for main heading
h2 is used for sub heading
h3 level 3 heading
h4 level 4 heading
h5 level 5 heading
h6 is the smallest heading
```

## PARAGRAPHS
A paragraph is used to define a block of similar text or content , image or link by using a `< p>` tag.

* We use `< p>` tags to define a paragraph.

* white space means creating extra space ,tabs or line breaks before or after a text.

### Line Breaks and Horizontal rules 

* `< br/>` tag is used to break a line inside the middle of a paragraph.

* you can add horizontal rule to break between sections using `< hr/>` tag. 

* empty elements are different they only has one tag.


### Strong and Emphasis

* Using `< strong> `element indicates that the content has strong importance.

* `< em>` element emphasis the meaning of the sentence in italic.

### Quotations

* `< blockquote>` element is used for longer quotes that take up an entire paragraph.

* `< q>` is used for shorter quotes that is within a paragraph.
* `< abbr>` element is used for abbreviation
* `< acronym>` element for acronym.
* `< cite>` is used to indicate where the citation is from.
* `< dfn>` is used to define a new term.
* `< address>` contain the contact address ofthe author.

# CSS

```
CSS is the language we use to style an HTML document.
Rules are made up of selectors and declarations that indicate what the elements should look like.
```
 **`Selectors`** indicate which element the rule applies to.
 **`declarations`**  within the block determines how the elements are formatted on a webpage.
**`Properties`** indicate the aspects of the element you want to change.

### External CSS

* is a separate CSS file that can be accessed by creating a link within the head section it includes href type and rel.

### Internal CSS

* is used to define a style for a single HTML page

### CSS selectors

> Css selectors are case sensitive, so they must match

* `Universal selector`: {} targets all the element on the page
* `Type selector`: matches element names (h1, h2, h3)
* `ID selector`: # element whose id attribute has a value
* `Child selector` :  matches an element that is a direct child of another


# Javascript

**DATA TYPES**

* `BIoolean`: It can have two values 'True or False'.
* `Number`: data type handles numbers.
* `String`: data type is closed in pair quotes''.

## Variable Rules
```
1. must begin with a letter or $ sign or (_) not a number.
2. do not use (-) or (.).
3. you cannot use **keywords** or **reserved** words.
4. all variables are case sensitive.
5. use a name that describes the kind of information.
6. use a capital letter for the first letter of every word after the first word ex: userName.
```
## Operators

* `Assignment operators`: (assign a value to a variable)
* `Arithmetic operators`: (perform a basic math)
* `Comparison operators`: (compare two value and return 'true or False').
* `Locgical Operators`: (combine expression and return 'true or False)
* `String Operators`: (combine multiple strings together).



## DECISIONS AND LOOPS
* `==` is epual to
* `===` strict equal to
* `!=` is not equal to
* `!==` strict not equal to
* `>` greater than
* `<` less than
* `>=` greater than or =
* `<=` less than or equal

**Logical Operators**

* `&&` - logical and 
* `||` -  logical or
* `!` -  logical not

**IF Statements**

_if_ statement evalutes or check a condition.

```
if ( score >= 50){
    pass();
}
```

_if ...else_ statement

```
if ( score >= 50){
    congratulate();
}
else{
    encourage();
}
```
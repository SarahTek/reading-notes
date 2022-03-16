# Error Handling and Debugging
Hoisting is JavaScript's default behavior of moving all declarations to the top of the current function or script.
* exeception- handling : handle errors and maintain a regular JavaScript code.
* Error objects helps where to find the mistakes are and browsers have tools to help you read them.
 ## Seven types of error objects
 - `Error`: Creates a new Error object.
 - `SyntaxError`: incorrect use of rules of the language.like a typo
 - `RefrenceError`: caused by variable that is not ddeclared or out of scope
 - `TypeError`:caused by tyring to use an object or method that doesn't exist
 - `RangeError`:caused by calling a function using numbers outside of its accepted range.
 - `URIEroor`: if this (/ ? & # : ;) are not escaped , they will cause error.
 - `EvalError`: indicates an error regarding the global eval() function. 

## Dealing with Errors
- debug the code, track down the source of the error using dev tools available in the browser in chrome, Firefox..
- handle the errors gracefully using try, catch and throw and finally statements.

# Understanding the JavaScript Call Stack


1. What is a ‘call’?
- The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.
2. How many ‘calls’ can happen at once?
- one at a time
3. What does LIFO mean?
- it means Last In First Out data structure ,primarily used for function invocation.
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
- 
```

function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();
```
5. What causes a Stack Overflow?
- when you've used up more memory for the stack than your program was supposed to use.


## JavaScript error messages

1. What is a ‘reference error’?
- when using a variable that is not declared or does not exist in the function
2. What is a ‘syntax error’?
- it happens when using incorrect use of syntax or invalid code.
3. What is a ‘range error’?
- creates an error when a value is not in the set or range of allowed values.
4. What is a ‘type error’?
- error shows up when a value is not of the expected type.
5. What is a breakpoint?
-A breakpoint is which helps the program to stop at a certain line of code that you want to break.
6. What does the word ‘debugger’ do in your code?
- it helps to identify incorrect code and analyze how a program flows.

### Resources
- [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)
- [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

# Forms
1. What is a ‘Controlled Component’?
 - A controlled component is a component that renders form elements and controls them by keeping the form data in the component's state.
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
- it will update the whenever the user types 

3. How do we target what the user is entering if we have an event handler on an input field?
- event.target.value
## The Conditional (Tenary) Operator Explained

1. Why would we use a ternary operator?
- We use ternary opertor help us to right in a single line of code and it is more compact and easy to read.
2. Rewrite the following statement using a ternary statement:
```
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```
```
x===y ? console.log(true): console.log(false)

```

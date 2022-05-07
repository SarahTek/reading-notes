# Thinking in React

1. What is the single responsibility principle and how does it apply to components?
- a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.
2. What does it mean to build a ‘static’ version of your application?
- static app is building a version that takes your data model and renders the UI but has no interactivity.
3. Once you have a static application, what do you need to add?
 - render() method.
4. What are the three questions you can ask to determine if something is state?
- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.
5. How can you identify where state needs to live?
- We need to work out which components rely on the state, which can potentially mutate it and which should own it.

## Higher-Order Functions

1. What is a “higher-order function”?
- Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions. 
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
- its returning m arrow functions and m is greater than n.
3. Explain how either map or reduce operates, with regards to higher-order functions.
- The result of map is always a new array. 
- the input collection is not modified.
- Map translates data from one type to another. Doesn’t necessarily mean that the data type changes - but you are changing from one form to another.

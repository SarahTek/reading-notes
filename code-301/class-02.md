# State and Props


1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
- According to the diagram, render happens before the componentDidMount.
2. What is the very first thing to happen in the lifecycle of React?
- The constructor() is the very first method called as the component is “brought to life.” The constructor method is called before the component is mounted to the DOM.

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
- constructor
- render
- React updates
- componentDidMount
- componentWillUnmount

4. What does componentDidMount do?
- It invokes the component immediately after its mounted.

 ## React State Vs Props

1. What types of things can you pass in the props?
- It can pass a value from parent component to child component  they are like (using arguments in function).

2. What is the big difference between props and state?
state is handled in the component and you can update it inside the component while props is are handled outside the component and must be updated outside the component
3. When do we re-render our application?
- if we want to update our application by using state.
4. What are some examples of things that we could store in state?
- we could store data or forms that could be updated by using state. 


### Resources
- [Web Dev Simplified React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

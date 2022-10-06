# Reading

Introducing Hooks

1. What was the motivation for introducing Hooks?

- Hooks let you use more of React's features without classes.
- You can write concise and clearer code.
- Hooks solve a wide variety of seemingly unconnected problems in React.

2. What changes are important regarding implementing Hooks versus Component Classes?

- Hooks are only used in functional components
- Hooks let you split one component into smaller functions based on what pieces are related
- Hooks let you use more of React’s features without classes.

3. Hooks allow you to reuse stateful logic without changing `component hierarchy`.

hooks api

1. Name two rules imposed by React Hook usage.

- Only call Hooks at the top level.
- Only call Hooks from React function components. 

2. How would you identify a custom Hook and why might you create one?

- If a function’s name starts with ”use” and it calls other Hooks, we say it is a custom Hook. custom hooks lets you reuse same common stateful logic within the component.

the state hook

1. What is a Hook?

- Hooks are functions that let you “hook into” React state and lifecycle features from function components

2. When would I use the useState Hook?

- useState is a Hook (function) that allows you to have state variables in functional components. You pass the initial state to this function and it returns a variable with the current state value (not necessarily the initial state) and another function to update this value.

3. If you were to add React state to a function component by declaring a state variable:

- What does calling useState do?
  - it declares a state variable
- What do we pass to useState as an argument?
  - the initial state
- What does useState return?
  - The current state and the function that updates the state.

## Resources

- [Introducing Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)
- [hooks api](https://reactjs.org/docs/hooks-overview.html)
- [the state hooks](https://reactjs.org/docs/hooks-state.html)
- [w3schools](w3schools.com/react/react_usestate.asp)

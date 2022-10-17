# Reading

useReducer hook

1. Name an alternative to the useState Hook.

- `useReducer`

2. Why might the useReducer Hook be preferable to the useState 
Hook?

- useReducer is usually preferable to useState when you have 
complex state logic that involves multiple sub-values or when the next state depends on the previous one

3. What are two ways to set the initial state?

- first way is to pass the initial state as a second argument

```
 const [state, dispatch] = useReducer(
    reducer,
    {count: initialCount}
  );
```

- You can also create the initial state lazily. To do this, you can pass an init function as the third argument. The initial state will be set to init(initialArg).

Ultimate Guide to useReducer

1. In terms of state, what does useReducer expect to receive as a parameter?

- the current state and the action.

2. What does useReducer return?

- useReducer returns an array that holds the current state value and a dispatch function to which you can pass an action and later invoke it. 

3. Explain dispatch to a non-technical recruiter.

- The dispatch is the second value returned from the useReducer Hook and can be used in our JSX to update the state

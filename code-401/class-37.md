# Reading

`Multiple Reducers Example`

1. Why create multiple reducers?

- We use actions to perform actions and we have reducers to modify and create change in our state of redux. Most of the time we have multiple actions to perform and for that we have multiple reducers.

2. How would you combine multiple reducers?

- You define multiple reducers to handle different pieces of your application's state, then compose these reducers together into one root reducer. The root reducer is then passed into the Redux createStore() method. In order to let us combine multiple reducers together, Redux provides the combineReducers() method.

3. How will you manage state as an immutable object? why?

- In Redux, the state is always predictable. If the same state and action are passed to a reducer, the same result is always produced because reducers are pure functions. The state is also immutable and is never changed

`Redux Docs: Using Combined Reducers`

1. combineReducers is a utility function to simplify the most common use case when writing `Redux reducers`.
2. Explain how combineReducers assembles the new state tree.

-  In order to assemble the new state tree, combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed

3. How would you define initial state in an app using combineReducers?

- There are two ways to define the initial shape and contents of the app's state. First, the `createStore` function can take `preloadedState` as its second argument. This is primarily intended for initializing the store with state. The other way is for the root reducer to return the initial state value when the state argument is `undefined`

`Redux Docs: Combined Reducer Syntax`

1. Why will you want to split your reducing functions as your app becomes more complex?

- As your app grows more complex, you'll want to split your reducing function into separate functions, each managing independent parts of the state.

2. The `combineReducers` helper function turns an object whose values are different reducing functions into a single reducing function you can pass to `createStore`.

3. What is a popular convention when naming reducers?

- A popular convention is to name reducers after the state slices they manage.

```
combineReducers({ todos: myTodosReducer, counter: myCounterReducer }) 
```


## Resoources

- [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)
- [Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)
- [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

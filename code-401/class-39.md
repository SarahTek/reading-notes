# Reading

`Redux Toolkit (RTK)`

1. What concerns are addressed by Redux Toolkit?

- The Redux Toolkit package is intended to be the standard way to write Redux logic. It was originally created to help address three common concerns about Redux:

  - "Configuring a Redux store is too complicated"
  - "I have to add a lot of packages to get Redux to do anything useful"
  - "Redux requires too much boilerplate code"

2. What does configureStore() do?

- configureStore(): wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

3. How would I use createSlice()?

- `createSlice` takes an object of reducer functions, a slice name, and an initial state value and lets us auto-generate action types and action creators, based on the names of the reducer functions that we supply. It also helps you organize all of your Redux-related logic for a given slice into a single file. 


`MobX`

1. What is Mobx?

- MobX is a battle-tested library that makes state management simple and scalable by transparently applying functional reactive programming.

2. How does MobX make it “impossible” to produce an inconsistent state?

- MobX makes state management simple again by addressing the root issue: it makes it impossible to produce an inconsistent state. The strategy to achieve that is simple: `Make sure that everything that can be derived from the application state, will be derived. Automatically.`

3. How would we build a reactive user interface?

- Use the `observable` decorator or 1observable(object or array)1 functions to make objects trackable for MobX.
- The `computed` decorator can be used to create functions that can automatically derive value from the state and cache them.
- Use `autorun` to automatically run functions that depend on some `observable state`. This is useful for logging, making network requests, etc.
- Use the `observer wrapper` from the `mobx-react-lite` package to make your React components truly reactive. They will update automatically and efficiently. Even when used in large complex applications with large amounts of data.


## Resources

- [Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)
- [MobX](https://mobx.js.org/getting-started.html)

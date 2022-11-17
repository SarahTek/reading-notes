# Reading

`Dan Abramov Redux Tutorials`

1. What is the first principle of Redux?

- Single Source of Truth. This means that we should only store one state object on our application, no more, no less.

2. what is a store and what do we use our reducers for within that store?

- Store is an object which provides the state of the application. Reducers are functions that take the current state and an action as arguments, and return a new state result.

3. Name three Redux store methods given to us by createStore and describe their use.

- reducer (Function): A reducing function that returns the next state tree, given the current state tree and an action to handle.

- [preloadedState] (any): The initial state. You may optionally specify it to hydrate the state from the server in universal apps, or to restore a previously serialized user session. If you produced reducer with combineReducers, this must be a plain object with the same shape as the keys passed to it. Otherwise, you are free to pass anything that your reducer can understand.

- [enhancer] (Function): The store enhancer. You may optionally specify it to enhance the store with third-party capabilities such as middleware, time travel, persistence, etc. The only store enhancer that ships with Redux is applyMiddleware().

4. Explain to a non-technical recruiter what combineReducers() does and why it is useful.

- Having multiple reducers become an issue later when we create the store for our redux. To manage the multiple reducers we have function called combineReducers in the redux. This basically helps to combine multiple reducers into a single unit and use them.

Bookmark and Review

[worlds easiest guide to redux](https://www.freecodecamp.org/news/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)

[testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)

[Redux Docs](https://redux.js.org/)

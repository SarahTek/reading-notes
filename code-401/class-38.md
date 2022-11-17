# Reading

`async actions`

1. Why use Redux middleware?

- Redux Middleware allows you to intercept every action sent to the reducer so you can make changes to the action or cancel the action. Middleware helps you with logging, error reporting, making asynchronous requests, and a whole lot more.

2. Consider the Redux Async Data Flow Diagram.Describe the flow in your own words.

- we first need to handle a user event in the application, such as a click on a button. Then, we call dispatch(), and pass in something, whether it be a plain action object, a function, or some other value that a middleware can look for.Once that dispatched value reaches a middleware, it can make an async call, and then dispatch a real action object when the async call completes.

3. How are we accommodating async in our Redux app?


`thunk middleware`

1. Why would you need `redux-thunk` middleware?

- Redux Thunk is middleware that allows you to return functions, rather than just actions, within Redux. This allows for delayed actions, including working with promises. One of the main use cases for this middleware is for handling actions that might not be synchronous, for example, using axios to send a GET request.

2. Redux Thunk middleware allows you to write action creators that return a function instead of an action.

3. Describe how any return value from the inner thunk function will be made available.

- Any return value from the inner function will be available as the return value of `dispatch` itself.


## Resources

- [async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)
- [thunk middleware](https://github.com/reduxjs/redux-thunk)

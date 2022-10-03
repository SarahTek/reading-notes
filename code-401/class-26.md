# Reading

React Hello world

1. What are the building blocks of a React app?

- Elements and Components.

2. What is the difference between an element and a React component?

- An element is what gets returned from the Components
- Components let you split the UI into independent, reusable pieces, and think about each piece in isolation.

3. What are some advantages of React’s component based architecture?

- it is reusable
- Faster development
- Repetition


introducing JSX

1. What is JSX and why do we use it?

- JSX stands for JavaScript XML. It is simply a syntax extension of JavaScript. It allows us to directly write HTML in React (within JavaScript code).

2. Describe the process of embedding JavaScript expressions in JSX.

- You can put any valid JavaScript expression inside the curly braces in JSX

3. Is it safe to embed user input in JSX? Explain.

- Yes It is safe. By default, React DOM escapes any values embedded in JSX before rendering them. Thus it ensures that you can never inject anything that’s not explicitly written in your application.


rendering elements

1. Explain what a React Component is to a non-technical friend.

- React Component are independent and reusable bits of code. Components let you split the UI into independent, reusable pieces, and think about each piece in isolation.
 
2. Describe mutability and React Components, specifically, how is the UI updated?

3. If changes are made to the UI, what does React update?

- React DOM compares the element and its children to the previous one, and only applies the DOM updates necessary to bring the DOM to the desired state.


## Resources

- [React Hello World](https://reactjs.org/docs/hello-world.html)
- [introducing JSX](https://reactjs.org/docs/introducing-jsx.html)
- [rendering elements](https://reactjs.org/docs/rendering-elements.html)

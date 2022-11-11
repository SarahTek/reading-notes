# Reading


1. With regard to the React Context API, what does a “provider” do?

- Every Context object comes with a Provider React component that allows consuming components to subscribe to context changes.The Provider component accepts a value prop to be passed to consuming components that are descendants of this Provider. One Provider can be connected to many consumers.

2. With regard to the React Context API, how would we implement a “consumer” role?

- Create context using the createContext method.
Take your created context and wrap the context provider around your component tree.
Put any value you like on your context provider using the value prop.
Read that value within any component by using the context consumer.

3. Specifically with Context, how are we “wrapping” components to achieve our goals?

- we wrap the components with the provider at the top root component

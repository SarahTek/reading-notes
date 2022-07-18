# Readings: Express REST API

## Review: ES6 Classes

1. Classes are a template for creating objects.
2. Can a class declaration be hoisted? YES
3. How would you describe a constructor and contextual “this” to a non-technical friend?

- A constructor is a special function that creates and initializes an object instance of a class and  this keyword refers to an object. Which object depends on how this is being invoked (used or called).

## Using Express Routing

1. Within Express, what does routing refer to?

- Routing refers to how an application’s endpoints (URIs) respond to client requests.

2. What is the difference between a route path and a route method?

- A route method is derived from one of the HTTP methods, and is attached to an instance of the express class.
- Route paths, in combination with a request method, define the endpoints at which requests can be made. 

3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

- it is appropiate to use next() to pass control to the next middleware function.

## Express Routing

1. What is an Express Router?

- Express Router is a routing mechanism that refers to how an application's endpoints (URIs) respond to client requests.

2. By what mean do we initialize express.Router() in an express server?

- using `app.route()` to call the `express.router()` and start  applying the routes there.

3. What do we use route middleware for?

- the use of route in middleware to define the endpoints at which requests can be made.

## Resources
- [ES6 classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
- [Using Express Routing](https://expressjs.com/en/guide/routing.html)
- [Express Routing](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)

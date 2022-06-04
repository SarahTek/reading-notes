# CRUD

## status code based on REST Methods

1. In your own words, describe what each group of status code represents:

- 100’s = information response wether th request will fail  before they start sending the body.
- 200’s = These are the success codes. They tell the client that its request was accepted. 
- 300’s = These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore.
- 400’s = These are the client error codes. They are all about invalid requests a client sent to a server.
- 500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.

2. What is a status code 202?
- Accepted
3. What is a status code 308?
- Permanent Redirect
4. What code would you use if an update didn’t return data to a client?
- 404 status code - Not Found
5. What code would you use if a resource used to exist but no longer does?
- 410 status code - Gone
6. What is the ‘Forbidden’ status code?
-  403 status code - Forbidden



## Build A REST with Node.js, Express and MongoDB

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
- because we don't want to commit that to our Github and anybody can see or use it and that is not safe.
2. What is middleware?
- Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle.
3. What does app.use(express.json()) do?
- The app.use() function adds a new middleware to the app. Essentially, whenever a request hits your backend, Express will execute the functions you passed to app.use() in order.
4. What does the /:id mean in a route?
- is a unique identifier assigned to every order that is protected by Route Package Protection
5. What is the difference between PUT and PATCH?
- is a method of modifying resource where the client sends data that updates the entire resource while patch sends partial data that is to be updated without modifying the entire data.
6. How do you make a default value in a schema?
7. What does a 500 error status code mean?
- it means that the server encountered an unexpected condition that prevented it from fulfilling the request.
8. What is the difference between a status 200 and a status 201?
- 200 indicates the request has succeeded . 201 status code mean a request is successful and resource is created.



## Resources
- [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
- [Build A REST API With Node.js, Express, & MongoDB - Quick ](https://www.youtube.com/watch?v=fgTGADljAeg)

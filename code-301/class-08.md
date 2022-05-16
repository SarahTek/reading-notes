# API Design and Best Practices

1. What does REST stand for?
- REST stands for Representational State Transfer.
2. REST APIs are designed around a resource. 
3. What is an identifier of a resource? Give an example.
- URI is one of the unique identifier.
4. What are the most common HTTP verbs?
- The most common HTTP verbs are GET,POST, PUT,PATCH AND DELETE.
5. What should the URIs be based on?
- URIs should be based on nouns(the resources) and not verbs ( the operation of the resource).
6. Give an example of a good URI.
- https://adventure-works.com/orders
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
- it means that requiring consumer to make tremendous amount of distinct API calls to get needed information about a resource. It is not a good thing. instead  denormalize the data and combine related information into bigger resources that can be retrieved with a single request.
9. What status code does an unsuccessful GET request return?
- status 404 (Not Found).
10. What status code does a successful POST request return?
- status code 201 (Created).
11. What status code does a successful DELETE request return?
- status code 204 (No Content).


## Resources
- [API Design and Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

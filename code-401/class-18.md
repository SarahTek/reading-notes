# Reading

AWS API Gateway Overview

1. What is Amazon API Gateway?

- Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.

2. Why is Amazon API Gateway an important part of the Serverless ecosystem?

- Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups.

3. How does API Gateway integrate with other AWS services?

 Many AWS services support integration with Amazon API Gateway, including:

- AWS Lambda: run Lambda functions to generate HTTP API responses.
- AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
- Amazon Cognito: provide authentication and authorization for your HTTP APIs.

AWS API Gateway

1. What are the some benefits of using Amazon API Gateway?

- API Gateway allows you to implement a fully managed authentication and authorization.
- Integration with multiple types of web services

2. What two API types might you choose from?

- RESTful APIs
- WEBSOCKET APIs

AWS DynamoDB Guide

1. What is DynamoDB?

- DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS)

2. Under what circumstances would you recommend DynamoDB over MongoDB?

- Applications with large amounts of data and strict latency requirements.
- Serverless applications using AWS Lambda: DynamoDB is accessible via an HTTP API and performs authentication & authorization via IAM roles, making it a perfect fit for building Serverless applications.
- DynamoDB's connection and security model make it a popular choice for use with serverless compute like AWS Lambda

AWS DynamoDB

1. Explain to a non-technical friend how DynamoDB works.

- Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale. DynamoDB offers built-in security, continuous backups, automated multi-Region replication, in-memory caching, and data import and export tools

Dynamoose

1. What is Dynamoose?

- Dynamoose is a modeling tool for Amazon's DynamoDB and heavily inspired by Mongoose.

2. What are some key features of Dynamoose?

- Type safety
- High level API
- Easy to use syntax
- DynamoDB Single Table Design Support
- Ability to transform data before saving or retrieving items
- Strict data modeling (validation, required attributes, and more)
- Support for DynamoDB Transactions
- Powerful Conditional/Filtering Support
- Callback & Promise support
- AWS Multi-region support

## Resources

- [AWS API Gateway Overview](https://www.serverless.com/guides/amazon-api-gateway)
- [AWS API Gateway](https://aws.amazon.com/api-gateway/)
- [AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)
- [AWS DynamoDB](https://aws.amazon.com/dynamodb/)
- [Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

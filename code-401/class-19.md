# Readings: AWS: Events

AWS SQS vs SNS

1. What is the difference betweeen SQS and SNS?

- `SNS` (Simple Notification Service) is a distributed publish-subscribe service. And `SQS` (Simple Queue Service) is distributed queuing service.

2. What are some use cases for both SNS and SQS?

- Choose SNS if:

  - You would like to be able to publish and consume batches of messages.
  - You would like to allow same message to be processed in multiple ways.
  - Multiple subscribers are needed.

- Choose SQS if:

  - You need a simple queue with no particular additional requirements.
  - Decoupling two applications and allowing parallel asynchronous processing.
  - Only one subscriber is needed.

AWS SNS and SQS

1. Describe how to use SQS and SNS in a “fanout” pattern.

- SNS uses a publisher / subcriber system by publishing topics where the subsriber will be notified of events that are delivered to that topic.
- SQS is distributed queuing system. Messages are not pushed to receivers. Receivers have to poll or pull messages from SQS. Messages can't be received by multiple receivers at the same time.

2. Explain how “push notifications” work, using SNS.

- Push Notifications are the alert messages that can be sent by the app publishers to the app user even when they are not actively using an app

SQS and SNS Basics

1. How might a large scale, distributed application make use of a Queue system like SQS?

- 

### Resources

- [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

- [AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)
- [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

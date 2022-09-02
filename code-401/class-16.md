# Reading: AWS: Cloud Servers

## AWS EC2

1. What is an EC2 Instance?

- it is essentially a virtual machine that provides secure, resizable compute capacity in the cloud.

2.Name 2 use cases for EC2.

- delivers secure, reliable, high-performance, and cost-effective compute infrastructure to meet demanding business needs.
- Build, test, and sign on-demand macOS workloads. Access environments in minutes, dynamically scale capacity as needed, and benefit from AWS’s `pay-as-you-go pricing`

3.Provide 1 reason to use ECS instead of Heroku.

- `pay-as-you-go pricing` or easy access to logs

### EC2 For Humans

1. Where can we find EC2 on the AWS Console?

- we can find the EC2 under the compute section.

2.Explain the general difference between T2 Micro and XL.

- T2 instances has a free tier eligible for one year with 1 vCPU and 1 GB memory.The t2. xlarge features 16 GiB of memory and 4 vCPU and It doesn't have free tier.

3.Explain a “Compute Cycle” to a non-technical friend.

- Compute cycles measure how much processing time your applications require on the cloud.

### Elastic Beanstalk

1. What is Elastic Beanstalk?

- Elastic beanstalk is an easy to use service that deploys, manages and scales web app services.

2.Describe the relationship between EC2 and Elastic Beanstalk.

- Elastic Beanstalk is one layer of abstraction away from the EC2 layer. Elastic Beanstalk will setup an "environment" for you that can contain a number of EC2 instances, an optional database, as well as a few other AWS components.

3.Name some benefits of using Elastic Beanstalk.

- provides productivity
- Flexible and Easy to Begin
- the ability to deploy a variety of applications on AWS, coded in a variety of programming languages like PHP, Java, Python, Ruby, Node.

## Resourcces

- [AWS EC2](https://aws.amazon.com/ec2/)
- [EC2 For Humans](https://www.youtube.com/watch?v=lZMkgOMYYIg)
- [Elastic Beanstalk](https://www.youtube.com/watch?v=SrwxAScdyT0)

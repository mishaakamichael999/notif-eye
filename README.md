Let’s create a telegram bot that will send daily notifications about how many days of the year went in percentage. For example, “7.92% of days of the year have already passed.”

Let’s make this development iterative.

1 iteration:
Spring boot application that runs logic locally. You can use scheduling for this.

2 iteration:
Add logic that clients could subscribe/unsubscribe from notifications. Add tests.

3 iteration:
Run the same application in docker-compose (db and application)

4 iteration:
It is nice to see your application running locally, but we need a more reliable solution. Let’s run our application on AWS EC2

5 iteration:
Now we see that AWS EC2 is too much for us. Let’s make our application run on AWS Lambda. For scheduling, we will use AWS EventBridge. For manual triggering, we’ll use API Gateway.

6 iteration:
Let’s create a React application that will provide a UI for us. It will show users and their status (subscribed/unsubscribed)

What we will learn:

- Spring boot
- Telegram API
- Junit/Mockito
- Postgresql
- Docker
- AWS Lambda
- AWS EC2
- AWS IAM
- AWS S3
- AWS EventBridge
- AWS API Gateway
- React, Typescript

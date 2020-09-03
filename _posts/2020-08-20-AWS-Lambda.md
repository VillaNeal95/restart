---
layout: post
title:  "AWS Lambda"
date:   2020-08-27
categories: jekyll update
---

## Functions Are Key

A few blog posts ago now, I discussed AWS Lambda, and how it can be used to respond to certain events happening. Lamdba is designed to be super accessible, and all the customer has to do is write a snippet of code and then upload it to AWS, who will ensure that it runs in response to the desired event. 

AWS describe Lambda as an event driven, serverless computing platform. What this means in laymans terms, is that code, originally uploaded by the developer, is run in response to events. You can use lambda for pretty much everything, however, a good practical example which most individuals could use it for would be to automate simple, repetitive tasks which occur periodically, and therefore wouldn't require the use of a full server at a time. 

You might want to schedule jobs such as processing data from forms which customers have filled out on your website, or you might want to make use of lambda in order to collect analytics, as a counter or to send a SNS (Simple Notification Service) alert to a user(s).

A good thing about AWS Lambda is that you only pay when the Lambda function is called, and not for the time when it is idle. So if you set up Lambda to provide notifications, you will only be charged when the chain of events leading up to the notification is in play. There is also a code editor which means that you can write code directly and then upload it via that, rather than having to make use of a third party code editor, such as Sublime Text or VS Code. 

The AWS Lambda Documentation shows some interesting use cases, some being from household names. Thomson Reuters "uses AWS Lambda to process up to 4000 events per second for its usage analytics service, and it took 5 months to deploy into production".

Another use case which you can see is extremely important and practical, but which people who use the service might not think about, is seen by The Seattle Times' use of AWS Lambda. The documentation states that "The Seattle Times uses AWS Lambda to resize images for viewing on different devices such as desktop computers, tablets and smartphones". Imagine if a lambda function wasn't present when a user tried to read the news on their phone and they were a paying customer! Thus, when the function is triggered, the resizing occurs, and AWS will receieve payment everytime that occurs. 

In summary, whilst application users might not appreciate the importance of Lambda functions, developers clearly value the services' versatility. In the next blog we will discuss Amazon RDS and DynamoDB.

---
layout: post
title:  "Foundation Stone Of The Cloud"
date:   2020-08-23
categories: jekyll update
---

## EC2 Instances & S3 Buckets 

The business model of cloud computing would have a huge gaping hole in it, were it not for EC2 Instances & S3 Buckets, the key Compute and Storage components of AWS. 

EC2 Instances are essentially servers, or computers, which stand on racks in large data center warehouses. EC2 stands for Elastic Compute Cloud. You will know what servers look like from various tv series and movies, which portray servers as large computers on racks with flashing green lights. 15 years ago, if you were to start a business yourself, it would have required you either to buy a computer and all of the racking equipment and things which enable the computer to send out traffic and receieve it, configuring the Network Access Control Lists and Firewall settings yourself.

Alternatively, you could have had the website hosted by various providers, but it would still have required you to provision things and pay accordingly, and the same flexibility would not have been present. Now, with the cloud, it is possible for one person to start a business from their bedroom in a few clicks on their laptop, with their clicks allowing them to select a server, the Amazon machine image they want (linux/windows, essentially an operating system), whether they want an all round, general purpose server or a server specialised, for example geared towards data intensive activities such as machine learning, and then the server is live. 

All of the infrastructure, such as the servers themselves, are established and looked after by amazon in secure data centers and users around the world provision resources on the same servers, having their own portion of the cloud in a VPC, which they can expand or contract according to their needs.

The huge amount of users means that cost based economies of scale are available, and amazon pass these on to the customers at various points. This basically means that what was once very expensive and required forward planning, can now be tailored on demand and stopped when no longer needed. 

S3 Buckets are the storage element of AWS. S3 stands for Simple Storage Service. They allow you to place objects into the "bucket", for example, if you set up a website similar to dropbox, you can invite users to drop files or photos into the bucket. You can then configure AWS to do something with those objects, such as setting up a Lambda function, which reacts when something else happens. So you might set your website to ping a notification to somebody when somebody else uploads a photo of them and has included them in the comment section. EC2 Instances combined with S3 Buckets allow applications to be built and used in many ways, and storage can be cheap, particularly when using S3 Infrequent Access or S3 Glacier. 

In the next blog post I will focus on another important area of AWS, Auto-Scaling groups, which allows for computing and storage power to increase or decrease according to the demand, reducing the likelihood of downtime or servers crashing due to excessive demand.

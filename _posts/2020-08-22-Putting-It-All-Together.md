---
layout: post
title:  "Putting It All Together!"
date:   2020-08-29
categories: jekyll update
---

## IAC & CloudFormation

Cloudformation is a service offered by AWS which makes it extremely easy for individuals and companies to put together something that is able to be run and hosted by AWS in a small amount of time. The CloudFormation models centers around templates, and these are used to detail what exactly is needed to run the individual's/company's services.

However, the beauty of CloudFormation is that the individual does not have to worry about how it is all put together. They are instructed to focus on what matters, i.e. focusing on the core business idea and getting across to the AWS team what exactly it is. They configure the template according to their requirements, and from that point onwards, AWS handle the underlying infrastructure and worry about ensuring it runs. This means that everyone can focus their attention and resources were they are best placed - The tech specialists at Amazon focusing on that aspect whilst those who know their business best can focus on the running of that. 

The AWS Cloudformation documentation shines a light on the process, stating "You create a template that describes all the AWS resources that you want (like Amazon EC2 Instances or Amazon RDS DB Instances), and AWS CloudFormation takes care of provisioning and configuring those resources for you. You don't need to individually create and configure AWS resources and figure out what's dependent on what; AWS CloudFormation handles that".

The underlying ethos behind CloudFormation is the concept of Infrastructure as Code. Infrastructure as Code is defined as the process of managing and provisioning computer data centers through machine-readable definition files, rather than physical hardware configuration or interactive configuration tools. 

Loosely translated in laymans terms, the ethos behind Infrastructure as code is the desire to try to understand what the user is asking for by giving them a template, and then figuring out how to translate those requirements into structured, codified form. The code can then be used repeatedly, for example, to automate certain update or patching processes each day or each month. The focus is placed on the automation of the code, rather than just being able to achieve a one-off objective.

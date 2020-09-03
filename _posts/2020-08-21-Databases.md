---
layout: post
title:  "Databases"
date:   2020-08-28
categories: jekyll update
---

## RDS & DynamoDB

I'm sure your familiar with databases as a word, but are you familiar with databases in relation to AWS? No? Well your in the right place, and hopefully keen to find out more ;) 

A database can be described as an organised collection of data, which is generally stored and accessed electronically via a computer system. Databases can make use of SQL, Structured Query Language, in order to search for things, or can be more dynamic in nature, and hence not require Structured Query Language in order to search for things. 

A SQL database basically requires the user to use certain, pre-defined, structured language in order to retrieve the data. They are known as Relational databases, and relational basically means that the database consists of data items with pre-defined relationships between them. The items are typically organised as sets of tables, with columns and rows as the presentational form. The tables are used to hold information about the objects to be represented in the database. 

SQL databases have a fixed schema. A schema, in basic terms, is essentially the structure of the database. SQL databases have a fixed structure, and are therefore good to use for complex queries. This can be both a positive and a negative, and there is plenty of debate online about which type of database is the best to use! An example of a SQL database service is MySql. 

SQL databases are vertically scalable, meaning that you have to add extra computing power, in the form of more servers, CPU or storage in order to scale up. This can be physically, or, if using AWS, virtually, via the console and command line. You may have come across the logo, which shows a majestic Dolphin leaping upwards!

DynamoDB is known as a NoSQL database. NoSQL stands for "not only SQL", and is an approach to database design that provides flexible structures for the storage and retrieval of data that is modelled in forms other than the tables used in relational databases. A non-relational database can also be described as a distributed database, and rather than being solely table based, they can consist of document based databases, key-value pair or graph databases. There is therefore more flexibility in regards to the structure of the database. 

Essentially, if your data requirements are not clear, or if the data is unstructured, its probably better to use a NoSQL database, such as DynamoDB. As the name suggests, it is dynamic, able to hold data forms other than tables, such as documents, key-value pairs etc, unlike a pre-defined, fixed structure database. 

The AWS DynamoDB documentation states that "Hundreds of thousands of AWS customers have chosen DynamoDB as their key-value and document database for mobile, web, gaming, ad tech, iot, and other applications that need low-latency data access at any scale". This clearly illustrates the versatility of the service, and shows that it is indeed dynamic and can be used in many different industries, businesses and use cases!

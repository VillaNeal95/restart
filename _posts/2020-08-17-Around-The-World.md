---
layout: post
title:  "Around The World"
date:   2020-08-24
categories: jekyll update
---

## Location, Location, Location!!

In the last blog post, we talked about Scaling groups and policies. When you deploy an application, you can choose which region you want the servers which you deploy your application to be in. You might be a business in North America and therefore prefer the data center to be on the same continent for peace of mind, because you believe that the legal system will protect the data and the rights of the dataholders will be respected. 

AWS has data centers in regions all around the world, including EMEA, APAC, North America, and India. If the majority of a business's customers are likely to be based in one region, it makes sense to deploy the application in those data centers, as there is likely to be a faster connection and a more stable connection. 

Applications deployed in one region can still be accessed in other regions aswell, and so companies are not restricting themselves geographically by not deploying their application in every data center. Amazons Cloudfront service allows websites to be cached in Edge locations, which are essentially outposts that allow websites and data to be cached periodically (decided by the user), which means that the site can be accessible, however it may not be updated automatically as fast as where the application is deployed, and so this is dependent on the user's needs. 

A news website would not want to have to long before it is updated, because by then the news will be old. cacheing is therefore good for static webpages which are unlikely to be updated too regularly, or for sites that are updated at regular intervals, such as weekly or monthly.

Each AWS Region consists of 2 or more Availability Zones, and these Availability Zones are physically and logically isolated from eachother, meaning that any incident in the zone surrounding one Availability Zone will not impact on the running of the other availability zone. For example, a tornado that hits the Miami Data center will not effect the data center in Las Vegas, which is not dependent in anyway on the continuous running of the Miami Data center. Amazon refers to this as highly redundant, and highly available, as each data center is able to run without depending on any other data center and therefore a website will remain live as long as a user continues to pay AWS. 

In the next blog post I will talk about High Availability and Edge Locations

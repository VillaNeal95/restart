---
layout: post
title:  "Automation In Action"
date:   2020-08-25
categories: jekyll update
---

## The Magic of Auto-Scaling Groups

Auto-Scaling Groups are simple, but extremely effective. They can be the difference between a business idea becoming the next big thing or falling into the abyss, never to be seen again!

Essentially, Auto-Scaling Groups enable someone to configure a cluster of EC2 instances to be able to respond according to the desired criteria. If you want to continuously maintain a certain number of servers, you can tell the auto scaling group to always ensure that this number of servers are in play at any time. This will mean that if an instance becomes unhealthy or is not responding, then it will be terminated and a fresh instance launched in its place, ensuring continuity and ability to service an application. 

The health of instances can be observed by using Cloudwatch, which allows metrics to be tracked, logged and saved for future reference. I will discuss Cloudwatch in a future blog post, as it is super useful and able to be used to record a variety of things. Cloudwatch can also be configured to send notifications if a threshold is exceeded, or if instances are unhealthy. This allows you to be proactive and reactive, ensuring nothing is left to stagnate and decline. 

Auto Scaling groups also enable scaling policies to be used. A scaling policy allows you to increase or decrease the number of instances in your group dynamically to meet changing conditions. You can select a minimum and maximum value, and according to the amount of traffic routed toward the application, the scaling policy will adjust itself constantly, ensuring that there is enough capacity to service the user base, but ensuring that there is not an oversupply of capacity and hence overcharging. The ability to handle varying loads of traffic can be extremely useful. A good example to use would be a derby day football match. 

If the 12:30pm kickoff is not a particularly enticing prospect for the neutral fan, the broadcaster might not have to handle too much traffic. Therefore the number of EC2 instances needed to host that match will be lower, as less people will have logged in to watch. However, immediately after that game and the post-game commentary has finished, a top of the table clash between 2 of the league's most supported teams is taking place, and this team has attracted not only a large portion of the football fans in the country, but all over the world. 

The broadcaster will suddenly be swamped by people from all over the world, in differing time zones, tuning in on mobile devices and laptops. This requires a much larger and robust cluster of EC2 instances to handle the traffic, and a the scaling policy will ensure that none of the users are left unable to watch the match due to a dearth of server capacity. This is important, because in the modern era, the customer has a plethora of options, and they could easily sign up to a competing service provider if a poor customer experience occured. Scaling groups and policies help to mitigate and avoid this scenario, whilst ensuring a good experience for the end user and a solid revenue stream for AWS. 

In the next blog post I will talk about Regions and Availability zones in AWS, and how they are able to provide a seamless service to ensure that the whole world is able to make use of AWS hosted services.

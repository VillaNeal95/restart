---
layout: post
title:  "Cloudwatch"
date:   2020-08-30
categories: jekyll update
---

## I Got A Feeling Somebody's Watching Me! 

Yes, the above is from the insanely popular Michael Jackson song, but its also basically how Cloudwatch operates! Cloudwatch is a service offered by AWS which allows for the collection of metrics, and is very useful, because a lot of things can be done with the collection of data. 

Cloudwatch enables you to collect a variety of information, such as detailed performance metrics, logs and metadata. Metadata is described as a set of data that describes and gives information about other  data. 

A simple illustration of metadata that most people can relate to would be the metadata for a CD. The artist's name, name of the album and the year the album was released can all be described as a set of data that gives information about other data, in this instance, the particulars about a CD. 

Metadata can also be used in other ways. For example, a telecommunications company might not know exactly what was said over a phone call, but they do however have information on who were the participants, the duration of the call, how many times the participants have previously communicated etc. It therefore isn't a surprise to see how this data about data could be lucrative for companies, and encourage them to try to monetise this data! This can be done in a number of ways, by targeting accquaintances and their networks of current customers by using the metadata they currently possess in order to achieve exponential growth of new customers. 

A key use of Cloudwatch is using it to monitor instances, and then implement a certain action when the criteria is met. For example, you can configure an alarm, which will alert you when a threshold you have set has been exceeded, or you can use Cloudwatch to automatically stop, start or terminate an instance/series of instances. This has the benefit of allowing you to use your time productively elsewhere, but also enables effective scaling in and out of instances, meaning the likelihood of downtime is significantly reduced. It also saves you having to navigate to the dashboard everytime you have been alerted that capacity has been reached, meaning simple tasks can be automated. This is useful if there are regular spikes in internet trafficm for example, if a streaming platform release a new episode at a certain time every week. 

Cloudwatch notifications are sent using the SNS (Simple Notification Service), and this can be via email or phone. Metrics are stored separately according to Region, but can be brought together via use of the Cloudwatch Cross-Region functionality. 

In the next blog post, I will talk about Version Control and Github.
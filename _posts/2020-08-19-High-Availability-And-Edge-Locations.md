---
layout: post
title:  "High Availabilty & Edge Locations"
date:   2020-08-26
categories: jekyll update
---

## Ensuring a Sterling Service

AWS calls its content delivery network Cloudfront. CloudFront is a low latency (fast!!) content delivery network, enabling the secure delivery of data, videos, and applications to customers globally with high transfer speeds. 

Basically, it turbocharges delivery of static and dynamic web content to end users. When briefly discussed in the last blog post, I mentioned that edge locations are a series of global AWS outposts. These outposts make use of Aws's content delivery network, Amazon Cloudfront. 

When a user requests content that is being served by cloudfront, the user is routed to the edge location that provides the lowest latency, ensuring that the content is delivered with the best possible performance. If the content is already in the edge location with the lowest latency, the content will be delivered via cloudfront immediately. 

If the content is not currently in the edge location, cloudfront will retrieve it from a defined endpoint- such as an s3 bucket, which we talked about earlier. The s3 bucket will have an endpoint, essentially a url link, that can be connected to via AWS. In future, that resource will now be in the edge location, so that when future users connect to the edge location, they will receive immediate delivery via cloudfront, the content delivery network.

As AWS only uses its own network, the number of networks which user requests must pass through is reduced by a significant degree. This lowers the latency and delivery time, whilst ensuring a greater data transfer rate. 

High Availability in AWS parlance means that the emphasis is placed firmly on keeping a business running in the event of data center, server, network, and storage transfer. Amazon want to reassure customers and potential customers, in addition to users, that they will be able to conmtinue to access content, regardless of what happens to any physical infrastructure or hardware which AWS are responsible for under the Shared Responsibility Model. 

Certain AWS services include highly available solutions as standard. AWS S3 and EFS (Elastic File System)automatically store data across different Availability Zones. Amazon EBS enables deployment of snapshots to various availability zones, enabling restoration to a point in time.

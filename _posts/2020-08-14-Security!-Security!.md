---
layout: post
title:  "Security! Security!"
date:   2020-08-21 
categories: jekyll update
---

## Cloud Security

You might have seen in the news recently about how the rise in homeworking caused by the onset of the pandemic led to a huge uptick in attempted cybercrime. As homeworking became the norm, cyber criminals knew that certain procesesses which are usually followed whilst working in the office may not be adhered to, particularly at the beginning of the pandemic, and therefore knew that this was an opportunity like no other which could potentially turn out to be very lucrative. 

Some companies have systems and processes and defences which apply to their office, and as nobody would be working from home, security would not normally be an issue. However, may companies could not afford to implement the expensive measures which were available to professional traders working at investment banks, and therefore they became vulnerable. 

Hackers can get into the computer in a variety of way, ranging from phishing and man in the middle attacks, to making use of keylogging systems and other forms of spyware or malware. Phishing is particularly common, as many of us who check our junk folders can attest to! However, some of these emails can be very sophisticated, and those with an untrained eye are not always able to sepearate genuine emails from malicious emails. 

AWS allows users to implement a range of security controls. When setting up serverless architecture, it is possible to configure Network Access Control Lists and Firewall settings to enable security according to need. For example, you might want to allow outbound traffic or but restrict inbound traffic, or vice versa, and therefore you would want to choose between stateless and stateful security solutions. 

AWS also allows companies/individuals and users to configure Identity Access Management settings according to their needs, and one of the best practices is to adhere to the principle of least privelege. This means that someone is granted the lowest level of privelege needed to do their job, and makes it less likely that human error can be responsible for the loss of data, and also less likely that data that is not needed by someone to do their job is exposed to fewer people. If the user requires greater access for whatever reason, they will need to manually request that and a systems admin would then have to configure their group/role policy. This adds a further layer of security, and makes it less likely for data to leak. 

Security solutions on AWS are serverless and can be added via a few clicks of the mouse on the management console or by using the AWS Command Line. Multi-Factor Authentication can be added to users, meaning that they will need to make use of an authenticator when signing in. AWS are responsible for security **OF** (physical security of data centers, regions, availability zones etc) the cloud, whereas AWS users are responsible for security **IN** the cloud (ensuring customer data is encrypted before uploaded to servers, Network and Firewall configuration etc).

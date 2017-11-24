---
layout:     post
title:      Targetting Customers With Real-Time On-Site Communications
date:       2017-04-21 10:00
summary:    How we 
category:   Software Engineering
tags:       Real Time, Messaging, Notifications, 
author:     ashley_broadley
image:      notifications.jpeg
---
### 

![Notififying customers](/images/notifications.jpeg)

Targetting customers with the right communications, at the right time, is a quite the technical challenge. There are many considerations to be made in terms of defining what 'Real-Time' means to the business and the technologies used in supporting that. Historically, the most Real-Time we've been with our communications is our CRM team sending out batches of emails or SMS to our customers, informing them of upcoming offers, new games and such like things. These 'offline' communications are often difficult to track conversions and often relate to a context that the customer is not aware of - or has since passed.

### Defining 'Real-Time' for Customer Messaging

Messaging customers about useful information, offers, or even games or events that are relevant to their interests ... something aout contextual messages...

### Discovering the Supporting Technologies

In order to meet the requirements for providing relevant and contextual messages to customers in a time efficient manner, we had to consider the technologies involved in helping deliver those bits of information. 

#### First up: The Event Service

For this, we chose Kafka. As previously posted about, Kafka is an Enterprise level message bus. It can operate at massive scale, in a massively performant manner. We already run a Kafka cluster internally here at Sky Betting & Gaming so the choice to use it was a pretty easy one.

#### Next: Getting our messages out there

HTTP API/WebSockets

#### And finally: Displaying to the customer

Client side implementaiton

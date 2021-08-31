# Event Driven Architecture

<br><hr>

> **Event-driven architecture** (_EDA_) is a software design pattern that enables an organization to detect “events” or important business moments

![Event Driven Architecture](https://media-exp1.licdn.com/dms/image/C5112AQFtkMSuM5oUkg/article-cover_image-shrink_720_1280/0/1582384474532?e=1635984000&v=beta&t=J3oz5qaTy_uEZQsR579s_qoARlyetGFdh9ZZCR0SHzI)

![Event Driven Architecture](https://www.researchgate.net/profile/Callum-Williams-Kinnaird/publication/335465510/figure/fig3/AS:797185583095808@1567075262321/FIFO-Mechanism-shows-how-a-FIFO-queue-operates-The-multiplexer-puts-the-incoming-flows.png)

<br><hr>

## What’s the difference between a FIFO and a standard queue ❓ [📁](https://medium.com/awesome-cloud/aws-difference-between-sqs-standard-and-fifo-first-in-first-out-queues-28d1ea5e153#:~:text=Standard%20queues%20guarantee%20that%20a,not%20introduced%20into%20the%20queue.)

> **Standard queues** guarantee that a message is delivered at least once and duplicates can be introduced into the queue.
> **FIFO queues** ensure a message is delivered exactly once and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue.

<br>

## How can the server be assured a message was properly received ❓

> by recieving a response, else will throw an error.

<br>

## What classic design pattern is best represented by event driven programming ❓ [📁](https://levelup.gitconnected.com/understanding-event-driven-design-patterns-for-microservices-659b3c9fb51f)

> Event Notification , It is the most basic pattern describing event-centric communication facilitated by the Event Store.

<br>

## How do you test an event driven system ❓ [📁](https://medium.com/dan-on-coding/testing-event-driven-systems-63c6b0c57517)

> **Unit Tests** are the most basic tests you will write
> Your unit test will interact with this class directly, passing various Order values to it, and verifying the tax has been calculated properly.

> Service Tests These tests verify the contract of services, that is given certain inputs, the service produces a certain output.

- Events have two primary functions:
  1. They are triggers of side effects somewhere in the system.
  2. They are also carriers of arbitrary data.

<br><hr>

## SNS

- simple _notification_ services.
- publisher/subsicriber system.
- publish a message about some topic, then will be delivered to many subsicribers with diffrent types.

## SQS

- simple _queue_ service.
- queueing service for message processing.
- the system must poll the queue to discover a new event.
- processing in the queue will be for single consumer.

[How To: Use SNS and SQS to Distribute and Throttle Events](https://www.jeremydaly.com/how-to-use-sns-and-sqs-to-distribute-and-throttle-events/)

![SNS vs SQS](https://res.cloudinary.com/practicaldev/image/fetch/s--0qV6AkDT--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dw71fyauz7yz9.cloudfront.net/video-upload__c8bc44f83cd41222de8ae55b55c63ef2/thumbs-video-upload__c8bc44f83cd41222de8ae55b55c63ef2-00001.png)

<br><hr>

[📁 AWS SNS and SQS - VID](https://www.youtube.com/watch?v=mXk0MNjlO7A)

# AWS: API, Dynamo and Lambda

<br><hr>

## What are serverless functions ❓ [📁](https://www.pubnub.com/blog/what-is-a-serverless-function/)

> **serverless functions** are single-purpose, programmatic functions that are hosted on managed infrastructure. These functions are hosted and maintained by cloud computing companies.

### who creates serverless functions? customers

### that allows developers to build and run applications without having to manage servers.

## If you were to create a system that emulated Lambda functions, how would you do it ❓ [📁](https://docs.aws.amazon.com/lambda/latest/dg/getting-started-create-function.html)

1. Open the Functions page on the Lambda console.

2. Choose Create function.

3. Under Basic information, do the following:

4. For Function name, enter my-function.

5. For Runtime, confirm that Node.js 14.x is selected. Note that Lambda provides runtimes for .NET (PowerShell, C#), Go Java, Node.js, Python, and Ruby.

6. Choose Create function.

## Describe how a CDN works ❓ [📁](https://www.imperva.com/learn/performance/what-is-cdn-how-it-works/)

> To minimize the distance between the visitors and your website’s server, a CDN stores a cached version of its content in multiple geographical locations <br>
> Each PoP contains a number of caching servers responsible for content delivery to visitors within its proximity.

<br><hr>

## Amazon API Gateway

> Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.
> API Gateway handles all the tasks involved in accepting and processing up to hundreds of thousands of concurrent API calls, including traffic management, CORS support, authorization and access control, throttling, monitoring, and API version management.

![Amazon](https://d1.awsstatic.com/serverless/New-API-GW-Diagram.c9fc9835d2a9aa00ef90d0ddc4c6402a2536de0d.png)

## What is DynamoDB?

> **DynamoDB** is a hosted NoSQL database offered by Amazon Web Services

> **Amazon DynamoDB** is a key-value and document database that delivers single-digit millisecond performance at any scale. It's a fully managed, multi-region, multi-active, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications. DynamoDB can handle more than 10 trillion requests per day and can support peaks of more than 20 million requests per second.

> Benefits of **Amazon DynamoDB**:

- _No_ servers to _manage_
- Enterprise _ready_
- _scale_
- safety
- Easy to use syntax
- Ability to transform data before saving or retrieving documents

> Benefits of **Amazon DynamoDB**:

- Serverless Web Apps
- Mobile Backends
- Microservices

<br>

- tables, items, and attributes;
- primary keys;
- secondary indexes;
- read and write capacity.

> Each item in a table is uniquely identified by a primary key. <br>
> There are two types of primary key: a **simple primary key** made up of just a partition key, and a **composite primary key** made up of a partition key and a sort key.

> The first kind of secondary index is a local secondary index. <br>
> The second kind of secondary index is a global secondary index

> provision read and write capacity units. These units allow a given number of operations per second.<br>
> DynamoDB also has autoscaling of your read and write capacity units.

<br><hr>

[📁AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway) <br>

[📁AWS API Gateway](https://aws.amazon.com/api-gateway/) <br>

[📁AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/) <br>

[📁AWS DynamoDB](https://aws.amazon.com/dynamodb/) <br>

[📁Dynamoose](https://dynamoosejs.com/getting_started/Introduction/) <br>

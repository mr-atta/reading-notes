# API 
![API ](https://www.browserstack.com/blog/content/images/2020/08/API-Blog-Thumbnail@2x.png)

# RESTful web API design

 ## What does REST stand for ❓
  > Representational State Transfer

 ## REST APIs are designed around a ____**resources**____.

 ## What is an identifer of a resource? Give an example ❓
   > which are any kind of object, data, or service that can be accessed by the client.

   > A resource has an identifier, which is a URI that uniquely identifies that resource. For example:
   `https://adventure-works.com/orders/1`

 ## What are the most common HTTP verbs?
   > GET, POST, PUT, PATCH, and DELETE.

 ## What should the URIs be based on?
   > URIs should be based on nouns (the resource) and not verbs.

 ## Give an example of a good URI.
   > https://adventure-works.com/orders    // Good

   > https://adventure-works.com/create-order    // Avoid

 ## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing? **it's bad thing**
   > "chatty" web APIs that expose a large number of small resources. 
   >  Such an API may require a client application to send multiple requests to find all of the data that it requires.

 ## What status code does a successful GET request return?
   > An HTTP GET request to the item's URI returns the details of that item
   > Retrieve all customers

 ## What status code does an unsuccessful GET request return?
   > Retrieve all orders for customer 1
   > Retrieve the details for customer 1

 ## What status code does a successful POST request return?
   > Create a new customer

 ## What status code does a successful DELETE request return?
   > Remove all customers

 ![methods](https://www.devopsschool.com/blog/wp-content/uploads/2018/09/http-method-put-post.jpg)
 ![methods](https://s3-us-west-2.amazonaws.com/assertible/blog/swagger-petstore-store-endpoints.png) 

 
 [♥️from](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design) 



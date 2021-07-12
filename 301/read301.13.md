
# HTTP Status Code to Use for Every CRUD App

 ## In your own words, describe what each group of status code represents:
  * 100’s = (informational status) header part of the request received, and they will go to transmission demand
  * 200’s = (success codes) the request is accepted
  * 300’s = (redirection codes) the resource isn’t available at the location
  * 400’s = (client error codes) invalid requests 
  * 500’s = (the server error codes) with overwhelmed servers or unreachable servers 

 ## What is a status code 202?
  > this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending
 ## What is a status code 308?
  > This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.
 ## What code would you use if an update didn’t return data to a client?
   > 204 No Content 
 ## What code would you use if a resource used to exist but no longer does?
  > 410 Gone
 ## What is the ‘Forbidden’ status code?
  > 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

# HTTP Status CodesPermalink
* A status code is a number higher than 100 and smaller than 600 that is part of a HTTP response. The first digit defines the class of the status. A status code comes with a reason phrase. The code is for programmatic recognition the phrase is for humans to understand what happened.


<hr><br><hr>

[📌 From](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
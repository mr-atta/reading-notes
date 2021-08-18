# Readings: Express REST API

## Review, Research, and Discussion

1. **Name 3 real world use cases where you’d want to change the request with custom middleware ?**

- when you want to manipulate the request (like:add current server time to the request)
- Add query params
- Handling error

2. **True or false: The route handler is middleware?**

- false, They are not middleware functions by definition

3. **In what ways can a middleware function end the process and send data to the browser?**

- `next(" ");` when face somthing bad , will end .
- `next();` when it finished the process .

4. **At what point in the request lifecycle can you “inject” middleware?**

- after the request
  - ![request lifecycle](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware/index/_static/request-delegate-pipeline.png?view=aspnetcore-5.0)

5. **What can cause express to error with “Request headers sent twice, cannot start a second response”**

- If you pass anything to the next() function (except the string 'route'), Express regards the current request as being an error and will skip any remaining non-error handling routing and middleware functions.
- When a POST request is sent to /api/route1 it will run every line in the callback. A Can't set headers after they are sent error message will be thrown because res.json() is called twice, meaning two responses are sent.

[📁](https://expressjs.com/en/guide/writing-middleware.html)
<br>
[📁](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-5.0)
<br>
[📁](https://expressjs.com/en/guide/error-handling.html)
[📁](https://stackoverflow.com/questions/7042340/error-cant-set-headers-after-they-are-sent-to-the-client?rq=1)
<br>

<br>
<hr>

## ES6 Classes [📁](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

## Using Express Routing [📁](https://expressjs.com/en/guide/routing.html)

## Express Routing [📁](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4#)

<br>
<hr>

### What can a middleware function do? [📁](https://expressjs.com/en/guide/using-middleware.html)

- Middleware functions can perform the following tasks:

* Execute any code.
* Make changes to the request and the response objects.
* End the request-response cycle.
* Call the next middleware in the stack.

<br>
<hr>

....

<!-- [📁]()
<br> -->

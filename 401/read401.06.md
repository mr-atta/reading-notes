# Authentication

### Explain what a “Singleton” is (in Computer Science terms) ?

- A **singleton** is a _class_ that allows only a single instance of itself to be created and gives access to that created instance.
- It is used in scenarios when a user wants to restrict instantiation of a class to only one object

### Explain how the Singleton pattern can be used with Node modules, specifically with classes ?

- Node.js modules can behave like Singletons, but they are not guaranteed to be always singleton. There are two reasons for this and both are mentioned in the official Node.js documentation:

1. Node’s module caching mechanism is case-sensitive:

2. Modules are cached based on their resolved filename

- In Node.js, files and modules are in one-to-one correspondence.

- This object has two methods and an internal private variable called “value”.

### If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

- Create a new project and npm init it… <br>
  `npm init ` <br>
  `npm install express --save`

- Create server.js with following code:

  - `const express = require('express');`
  - `const app = express();`

  * ` app.get('/', (req, res, next) => {`<br>
    `res.send('Welcome Home');`<br>
    `});`<br>

  * `app.listen(3000);`

- Run the server by `node server.js`
- local host: http://localhost:3000 >>> should see “Welcome Home” printed in your browser.

* In Express, you can set up middleware to be “global” middleware; meaning it will be called for every incoming request.
  - `app.use((req, res, next) => {`<br>
    `console.log(req);`<br>
    `next();`<br>
    `});`<br>

[link](https://www.techopedia.com/definition/15830/singleton) <br>
[link](https://medium.com/@lazlojuly/are-node-js-modules-singletons-764ae97519af) <br>
[link](https://developer.okta.com/blog/2018/09/13/build-and-understand-express-middleware-through-examples#express-request-logging-middleware-example) <br>

### Preparation Materials

[Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html) <br>
[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication) <br>
[OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html) <br>
[bcrypt docs](https://www.npmjs.com/package/bcrypt) <br>

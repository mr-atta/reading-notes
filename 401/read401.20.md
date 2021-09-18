# Component Based UI

![UI](http://derickbailey.com/wp-content/uploads/2015/08/webcomponents.jpg)

<br><hr>

## Review, Research, and Discussion

## Name 5 Javascript UI Frameworks (other than React)❓ [📁](https://trio.dev/blog/javascript-framework)

- The 5 Most Popular JavaScript Frameworks:

  1.  Node. js. Node.
  2.  Vue. js. Vue.
  3.  AngularJS.
  4.  Ember. js.
  5.  React.

<br>

> AngularJS is maintained by Google and addresses common complications in building single-page applications (SPAs).

> React is a JavaScript framework developed by Facebook that simplifies the process of building interactive UIs.

## What’s the difference between a framework and a library❓ [📁](https://trio.dev/blog/javascript-framework)

![framework vs library](https://csharpcorner-mindcrackerinc.netdna-ssl.com/UploadFile/a85b23/framework-vs-library/Images/DqCkT.png)
![framework vs library](https://www.digitaltechmedia.in/wp-content/uploads/2020/11/framework-vs-library-dtm.jpg)

- In JavaScript’s case, this base includes a collection of code libraries. The libraries compile code that elicits specific functionality for the specific type of app you may be working on. In essence, the framework will define the structure of the entire application.

<br>
<br>

### Hello World

- is the smallest React example:

## JSX

> JSX >>> `const element = <h1>Hello, world!</h1>;`

### What Is JSX? [📁](https://www.reactenlightenment.com/react-jsx/5.1.html)

- JSX is an XML/HTML-like syntax used by React that extends ECMAScript so that XML/HTML-like text can co-exist with JavaScript/React code

<br>

- Specifying Children with JSX
  > If a tag is empty, you may close it immediately with />, like XML: `const element = <img src={user.avatarUrl} />;`

* and can contain children

<br>

- JSX Prevents Injection Attacks
  > It is safe to embed user input in JSX:

`const title = response.potentiallyMaliciousInput;`
`// This is safe:`
`const element = <h1>{title}</h1>;`

- JSX Represents Objects
  > Babel compiles JSX down to React.createElement() calls.

<br>
<br>

[📁 react hello world](https://reactjs.org/docs/hello-world.html) <br>

[📁introducing JSX](https://reactjs.org/docs/introducing-jsx.html) <br>

[📁rendering elements](https://reactjs.org/docs/rendering-elements.html) <br>

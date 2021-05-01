# ***THE OBJECT***
- **Object is the basic building unit of the program.**
![Object 1](https://www.geeksread.com/wp-content/uploads/2018/04/Lesson-24-Objects-in-JavaScript.png)
  > "Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names."(PROPERTIES , METHODS)

* If we need to use a variable as part of an object, called a *property*, It tell us information about the object.
* a *method* is a function when be part of an object, It is the tasks that are associated with the object.
* properties and methods have a name and a va lue. The name is called a key.
* You cannot put two keys with the same name.
* The value of a method is always a function.



- ![ 3](https://image.slidesharecdn.com/introductiontooojs-140127004826-phpapp01/95/introduction-to-object-oriented-javascript-6-638.jpg?cb=1390783865)     
  - Almost "everything" can be an object :
    - Booleans can be objects (with the new keyword)
    - Numbers can be objects (with the new keyword)
    - Strings can be objects (with the new keyword)
    - Dates are always objects
    - Maths are always objects
    - Regular expressions are always objects
    - Arrays are always objects
    - Functions are always objects
    - Objects are always objects

* Literal notation is the most popular way to create objects.

### Accessing an object and dot notation 
![Accessing Object](https://bunlong.github.io/assets/img/dot-notation-vs-bracket-notation-to-access-object-properties-in-javascript.png)

* The content of the page is updated with data from this object.
* To access a property of this object, the object name is followed by a dot (the period symbol) and the name of the property that you want.
* Similarly, to use the method, you can use the object name followed by the method name.


## Document Object Model (DOM)
![DOM](https://bitsofco.de/content/images/2018/11/HTML-to-Render-Tree-to-Final.png)
- "**The Document Object Model** (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window."

![DOM tree](https://info340.github.io/img/html/dom-tree.jpg)
#### **DOM tree** 
  * a tree structure wherein each node is an object representing a part of the document.
  * DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
  * You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax.
#### **Application Programming Interface (API)** 
  - let programs (and scripts) talk to each other.
  - A Web API is an application programming interface for the Web.
  - A Browser API can extend the functionality of a web browser.
  - A Server API can extend the functionality of a web server.
- ELEMENT NODES , describe the structure of an HTML page.  
- "Each node is an object with methods and properties."
- Whenever a DOM query can return more than one node, it will always return a Nadel i st.

#### DOM tree steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.
- Can return one element, or they may return a Nodelist, we may use id (or any) for Customizable.
> ![.Getelement by id](https://i.ytimg.com/vi/zZA5qSE6qy8/maxresdefault.jpg)
- *Node-list* is a type of object called a collection. 
  - Nodelists have a method called item(), they return an individual node 
- we can use sentences like: for , if ...  in it.
- An element node can contain multiple text nodes and child elements that are siblings of each other.

- ![add-remove](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-Vd6fv4f30RXzkY91RXt7g252e1e-SSlUbSXTkZbpJ1fnv-3-8KAmGM7goCNSn4XeaEI&usqp=CAU)
- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).
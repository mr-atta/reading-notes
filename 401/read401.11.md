# Event Driven Applications

<br>

## Why is access control important ❓[📁](https://www.inform-consult.com/why-is-access-control-important/)

- When implemented effectively, they mitigate the risk of information being accessed without the appropriate authorisation, unlawfully and the risk of a data breach.

## Describe an application that would need access control ❓

- If you have application and you need to give access to some of the users to do/reach something and the other uses can't.
- Then you will need to use access control to distinguish between the rights of users

## What is a role used for ❓[📁](https://www.imperva.com/learn/data-security/role-based-access-control-rbac/#:~:text=Most%20large%20organizations%20use%20role,need%20to%20do%20their%20jobs.)

- Most large organizations use role-based access control to provide their employees with varying levels of access based on their roles and responsibilities.

## Why is role based access control more scalable than discretionary or mandatory access control ❓[📁](https://www.imperva.com/learn/data-security/role-based-access-control-rbac/)

- To most business applications, RBAC is superior to ACL in terms of security and administrative overhead.
- ACL is better suited for implementing security at the individual user level and for low-level data.
- while RBAC better serves a company-wide security system with an overseeing administrator.

<br>
<br>

## Event

- Every time you interact with a webpage through it’s user interface, an event is happening. When you click a button a click event is triggered. When you press a key a keydown event is triggered.

* EventEmitter
  - The EventEmitter instance will emit its own 'newListener' event before a listener is added to its internal array of listeners.
  - Node.js natively provides us with a useful module called EventEmitter that allows us to get started incorporating Event-Driven Programming in our project right away.

> `const EventEmitter = require('events').EventEmitter;` <br> > `const myEventEmitter = new EventEmitter;`

- lestin

  > `event.on('-event name-', -call back fun-);`

- callback
  > `events.emit('-event name-', -call back fun-);`

* To remove event listeners in EventEmitter we can use the **removeListener** or **removeAllListeners** method.

<br>
<br>

[📁 Event Driven Programming](https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)

<br>

[📁 Node docs: events](https://nodejs.org/api/events.html)

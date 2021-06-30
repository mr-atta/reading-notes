![react](https://miro.medium.com/max/2128/1*KN7zbaWkbm5E71zZWfTf7A.gif) 

# Thinking In React 🤔



 ### How would you break a mock into a component heirarchy ❓
 > 👉 Break The UI Into A Component Hierarchy·
 > 👉 Build A Static Version in React ·
 > 👉 Identify The Minimal (but complete) Representation Of UI State.

 ### What is the single responsibility principle and how does it apply to components❓
 * SRP
 *  a computer-programming principle that states that every module, (class or function) should have responsibility over a single part of that program's functionality, and it should encapsulate that part.
 * a **component** should be only done **one thing**, when finished it will move on. **component**  decomposed into smaller subcomponents.

 ### What does it mean to build a ‘static’ version of your application❓
 * That takes your data model and renders the UI but has no interactivity. To build a static version of your app that renders your data model.

 ### Once you have a static application, what do you need to add?
 * You will want to build components that reuse other components and pass data using props. props are a way of passing data.

 ### What are the three questions you can ask to determine if something is state❓
 > 👉 Is it passed in from a parent via props? If so, it probably isn’t state.

 > 👉 Does it remain unchanged over time? If so, it probably isn’t state.
 
 > 👉 Can you compute it based on any other state or props in your component? If so, it isn’t state.

 ### How can you identify where state needs to live❓
 * Identify every component that renders something based on that state.
 * Find a common owner component (a single component above all the components that need the state in the hierarchy).
 * Either the common owner or another component higher up in the hierarchy should own the state.
 * If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

![Thinking In React](https://miro.medium.com/max/3410/1*Dee4cg5Hzg7JME1A9tjZJQ.png) 


> React’s one-way data flow





[♥️from](https://reactjs.org/docs/thinking-in-react.html) 
[♥️from](https://en.wikipedia.org/wiki/Single-responsibility_principle) 


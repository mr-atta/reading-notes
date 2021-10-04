# Redux - Asynchronous Actions

<br>
<hr>

## How granular should your reducers be ❓ [📁]()

> Reducer functions should only depend on their state and action arguments, ... subscribed to the Redux store and reading data at a more granular level.

## Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched❓ [📁](https://sayefdeen.github.io/reading-notes401/class-38)

> Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
> Well, it is a Pro more than a Con since we have to change multiple states in multiple components, the fact that all the reducers can listen when the action is dispatched can reduce a lot of work, each reducer can provide a different logic to the same dispatcher.

## Name a strategy for preventing the above❓ [📁]()

> Make a reducer for each component that will be affected by the dispatcher

<br>
<br>

# Redux

> ![Redux](https://labs.tadigital.com/wp-content/uploads/2020/04/getting-started-with-redux-1096x453.png)

<br>

- **Redux** helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test.

## Redux Thunk

> Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store’s dispatch method, which is then used to dispatch regular synchronous actions inside the function’s body once the asynchronous operations have been completed.

- useful when utilizing a Redux store and relying upon external APIs.

![Redux](https://redux.js.org/assets/images/ReduxAsyncDataFlowDiagram-d97ff38a0f4da0f327163170ccc13e80.gif)

- There are two very popular middleware libraries that allow for side effects and asynchronous actions: Redux Thunk and Redux Saga.

## [📌 async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic) <br>

## [📌 thunk middleware ](https://github.com/reduxjs/redux-thunk) <br>

## [📌 redux thunk](https://alligator.io/redux/redux-thunk/) <br>

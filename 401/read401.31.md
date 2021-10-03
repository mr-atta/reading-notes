# Redux - Combined Reducers

<br>
<hr>

## Why choose Redux instead of the Context API for global state❓ [📁](https://www.codehousegroup.com/insight-and-inspiration/tech-stream/using-redux-and-context-api#:~:text=Context%20API%20is%20easy%20to,creating%20unnecessary%20work%20and%20complexity.)

> Context API is easy to is use as it has a short learning curve. It requires less code, and because there's no need of extra libraries, bundle sizes are reduced. <br>
> Redux on the other hand requires adding more libraries to the application bundle. The syntax is complex and extensive creating unnecessary work and complexity.

## What is the purpose of a reducer ❓ [📁](https://www.pluralsight.com/guides/how-to-write-redux-reducer)

> In Redux, a reducer is a pure function that takes an action and the previous state of the application and returns the new state. The action describes what happened and it is the reducer's job to return the new state based on that action. It may seem simple, but it does have to be a pure function with no side effects.

## What does an action contain❓ [📁](https://www.tutorialspoint.com/redux/redux_actions.htm#:~:text=Actions%20are%20the%20only%20source,from%20your%20application%20to%20store.&text=const%20ITEMS_REQUEST%20%3D%20'ITEMS_REQUEST'%3B,totally%20up%20to%20the%20developer.)

> Actions are the only source of information for the store as per Redux official documentation.

## Why do we need to copy the state in a reducer❓ [📁]()

> If the new state is different, the reducer must create new object, and making a copy is a way to describe the unchanged part.

<br>
<br>

# Redux

> ![Redux](https://labs.tadigital.com/wp-content/uploads/2020/04/getting-started-with-redux-1096x453.png)

<br>

- **Redux** helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test.

## Combined Reducers

> the most common approach to writing reducer logic for that state shape is to have “slice reducer” functions, each with the same (state, action) signature, and each responsible for managing all updates to that specific slice of state.

> As our application grows and becomes more complex, we can have multiple reducers each managing independent parts of the state. The combineReducers() helper function turns an object whose values are different reducing functions into a single reducing function that we can pass to createStore().

## [🎥 Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE) <br>

## [📌 Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/) <br>

## [📌 Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/) <br>

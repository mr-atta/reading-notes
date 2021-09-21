# Advanced State with Reducers

<br><hr>

## Review, Research, and Discussion

## How can we ensure that an effect hook runs only once ❓ [📁](https://gosink.in/react-js-how-to-render-useeffect-only-once/)

> If we pass an empty array [] , it just renders the component only once like componentDidMount.

## Can useState() update more than one state variable at the same time ❓ [📁](https://stackoverflow.com/questions/53574614/multiple-calls-to-state-updater-from-usestate-in-component-causes-multiple-re-re#:~:text=You%20could%20combine%20the%20loading,it%20replaces%20the%20object%20entirely.)

> Unlike the setState in class components, the setState returned from useState doesn't merge objects with existing state, it replaces the object entirely.

## Is useState() synchronous ❓ [📁](https://www.linkedin.com/pulse/provide-callback-usestate-hook-like-setstate-saransh-kataria/)

> **useState and setState** _both_ are **asynchronous**. They do not update the state immediately but have queues that are used to update the state object.

<!-- <br>
<br> -->

<!-- #### useState -->

<!-- ![]() -->

<br>
<br>

## useReducer

- `const [state, dispatch] = useReducer(reducer, initialArg, init);`

* useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one.
* useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

## Ultimate Guide to useReducer

- useReducer helps you manage complex state logic in React applications. When combined with other Hooks like useContext, useReducer can be a good alternative to Redux or MobX — indeed, it can sometimes be an outright better option.

### How does useReducer work?

- useReducer returns an array that holds the current state value and a dispatch function, to which you can pass an action and later invoke.

<br>
<br>

[📁 useReducer hook ](https://reactjs.org/docs/hooks-reference.html#usereducer) <br>
[📁 Ultimate Guide to useReducer ](https://blog.logrocket.com/guide-to-react-usereducer-hook/) <br>

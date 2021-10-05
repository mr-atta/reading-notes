# Redux - Additional Topics

<br>
<hr>

## What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application❓ [📁](https://stackoverflow.com/questions/39356517/correct-way-to-pre-load-component-data-in-reactredux#:~:text=1%20Answer&text=The%20most%20'redux%2Dlike',Component%20that%20wraps%20your%20app.)

> The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method of a Higher Order Component that wraps your app.

## When using a thunk/async action that dispatches the actual action, which do you export from your reducer❓ [📁](https://redux.js.org/assets/images/ReduxAsyncDataFlowDiagram-d97ff38a0f4da0f327163170ccc13e80.gif)

> The state

<br>
<br>

## thunk

> Redux Thunk is a middleware that allows you to call the action creators that return a function(thunk) which takes the store’s dispatch method as the argument and which is afterwards used to dispatch the synchronous action after the API or side effects has been finished.

<br>

# Redux

> ![Redux](https://labs.tadigital.com/wp-content/uploads/2020/04/getting-started-with-redux-1096x453.png)

### Redux Toolkit (RTK)

> The Redux Toolkit package is intended to be the standard way to write Redux logic.

> It includes several utility functions that simplify the most common Redux use cases, including store setup, defining reducers, immutable update logic, and even creating entire “slices” of state at once without writing any action creators or action types by hand. It also includes the most widely used Redux addons, like Redux Thunk for async logic and Reselect for writing selector functions, so that you can use them right away.

> The official, opinionated, batteries-included toolset for efficient Redux development.

### Why Use Redux Toolkit ❓

> makes it easier to write good Redux applications and speeds up development

### Redux Toolkit included :

- configureStore()
- createReducer()
- createAction()
- createSlice
- createAsyncThunk
- createEntityAdapter

### Tutorials Overview

> The Redux core docs site at https://redux.js.org contains the primary tutorials for learning Redux, including how to use Redux Toolkit and React-Redux together.

<br>

## [📌 Redux Toolkit (RTK) ](https://redux-toolkit.js.org/) <br>

## [📌 Tutorial ](https://redux-toolkit.js.org/tutorials/overview) <br>

## [📌 MobX ](https://mobx.js.org/getting-started.html) <br>

## [📌 HookState ](https://hookstate.js.org/) <br>

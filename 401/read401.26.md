# Context API - Behaviors

<br>
<hr>

## Review, Research, and Discussion

## When you have multiple contexts, what component type should you use (class/function) and why ❓ [📁](https://reactjs.org/docs/context.html)

> function <br>
> more effecience and less complexity, to deal with multiple contexts

## What are some good use cases for using the Context API for global state ❓ [📁](https://reactjs.org/docs/context.html)

- Using context, we can avoid passing props through intermediate elements.
- Context is primarily used when some data needs to be accessible by many components at different nesting levels.

## How can you best test context ❓ [📁](https://www.samdawson.dev/article/react-context-testing)

> _The best way to test Context_ is to make our tests unaware of its existence and avoiding mocks. We want to test our components **in the same way** that developers would **use** them **_(behavioral testing)_** and the way they would **run** in our applications **_(integration testing)_**.

<hr>
<br>

## Behavioural Testing

> Behavioural Testing is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.

## What is context behavior?[♦](https://www.alleydog.com/glossary/definition.php?term=Context)

> This term refers to the situation or circumstances in which an event occurs...the particular setting in which the event occurs. For example, when attempting to understand behavior, it is important to look at the situation or circumstances present at the time of the behavior.

<br>

## Context

> Context provides a way to **pass data through the component tree without having to pass props down manually at every level**.

### When to Use Context

- Using context, we can avoid passing props through intermediate elements.
- Context is primarily used when some data needs to be accessible by many components at different nesting levels.

- **But** use it sparingly because it makes component reuse more difficult.

#### note : If you only want to avoid passing some props through many levels, **component composition** is often a simpler solution than context.

## API

- React.createContext
  > `const MyContext = React.createContext(defaultValue);`

<br>

## hooks and context example

### Snackbars in React: An Exercise in Hooks and Context.

![Snackbars](https://ganzio.org/wp-content/uploads/2021/04/1618944141_401_The-problem-of-snackbars-and-what-to-use-instead.png)

- **Snackbars** inform users of a process that an app has performed or will perform. They appear temporarily, towards the bottom of the screen.

> `const { addAlert } = useSnackBars()` <br> > `...`<br> > `addAlert('Your profile is updated!')`<br>

<br>
<hr>
<br>

### Preparation Materials links

[📌 context api](https://reactjs.org/docs/context.html) <br>

[📌 hooks and context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b) <br>

[📌 react context links](https://github.com/diegohaz/awesome-react-context) <br>

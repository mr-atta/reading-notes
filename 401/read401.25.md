# Context API

<br>
<hr>

## Review, Research, and Discussion

## Describe use cases useState() 🆚 useReducer()❓ [📁](https://reactjs.org/docs/hooks-reference.html#:~:text=useReducer%20is%20usually%20preferable%20to,dispatch%20down%20instead%20of%20callbacks.)

> useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one.
> ![useState vs useReducer](https://res.cloudinary.com/practicaldev/image/fetch/s--1ICd6TAL--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/k0z9r0fyhojaytokogf2.JPG)

## Why do custom hooks need the use prefix❓ [📁](https://stackoverflow.com/questions/66151248/do-react-hooks-really-have-to-start-with-use)

> the "use" prefix also helps in easily identifying if a function is a custom hook.

## What do custom hooks usually do❓ [📁](https://reactjs.org/docs/hooks-custom.html#:~:text=Custom%20Hooks%20are%20a%20mechanism,a%20Hook%20gets%20isolated%20state.)

> **Custom Hooks** are a mechanism to reuse stateful logic , _but_ every time you use a custom Hook, all state and effects inside of it are fully isolated. How does a custom Hook get isolated state? Each call to a Hook gets isolated state.

## Using any list of custom hooks, research and name one that you think will be useful in your applications❓

> useState

## Describe how a hook that fetches API data might work❓ [📁](https://designcode.io/react-hooks-handbook-fetch-data-from-an-api)

> Put the fetchData function above in the useEffect hook and call it

- [exsampel](https://designcode.io/react-hooks-handbook-fetch-data-from-an-api) , [OR](https://stackoverflow.com/questions/55484033/reactjs-how-to-call-useeffect-hook-only-once-to-fetch-api-data)

<br>
<hr>
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

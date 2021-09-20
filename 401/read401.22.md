# Component Lifecycle / useEffect() Hook

<br><hr>

## Review, Research, and Discussion

## Why do we not need more .html pages in a multi-page React app❓ [📁](https://www.techomoro.com/how-to-create-a-multi-page-website-with-react-in-5-minutes/)

> Because React app consists of a single HTML file index.html. The views are coded in JSX format as components. <br>
> And when we need to build multi-page websites in React we use multiple routes instead of multiple pages to handle them.

## If we wanted a component to show up on every page, where would we put it and why❓

- Inside a `<Route />`

## What does routing do with the components that were rendered when a new route is requested❓ [📁](https://medium.com/the-andela-way/understanding-the-fundamentals-of-routing-in-react-b29f806b157e)

> When the router’s path and location are successfully matched, a match object is created. This object contains information about the URL and the path. This information can be accessed as properties on the match object.

- properties:
  - url : A string that returns the matched part of the URL
  - path : A string that returns the route’s path
  - isExact : A boolean that returns true if the match was exact
  - params : An object containing key-value pairs that were matched by the Path-To-RegExp package.

## What does props.children contain❓ [📁](https://stackoverflow.com/questions/49706823/what-is-this-props-children-and-when-you-should-use-it)

> it is used to display whatever you include between the opening and closing tags when invoking a component.

## How do useState() and this.setState() differ❓

> setState() Class Component

<br>

> useState() Functional Component

#### useState

![useState](https://freecontent.manning.com/wp-content/uploads/managing-component-state_04.png)

<br>
<br>

### State Hook

> Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.

### Mounting and Un-Mounting

> Mounting a file system attaches that file system to a directory (mount point) and makes it available to the system. The root `/` file system is always mounted. Any other file system can be connected or disconnected from the root `/` file system.
> These files are not permanently affected by the mounting process, and they become available again when the file system is Un-Mounting.

<br>
<br>

## [ effects hook 📂 ](https://reactjs.org/docs/hooks-reference.html)

> The Effect Hook lets you perform side effects in function components. <br>

> The function passed to useEffect will run after the render is committed to the screen. <br>

> By default, effects run after every completed render, but you can choose to fire them only when certain values have changed.

[📁 effects hook ](https://reactjs.org/docs/hooks-effect.html) <br>

<!-- [📁]() <br>
[📁]() <br>
[📁]() <br> -->

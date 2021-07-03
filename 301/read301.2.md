 ![State and Props](https://miro.medium.com/max/2128/1*KN7zbaWkbm5E71zZWfTf7A.gif)


# React: Component **Lifecycle** Events 🌱

   * React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states. 

 ## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?  **the ‘render’ first.**

 ## What is the very first thing to happen in the lifecycle of React? **constractor.**

 ## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates ?? 
   > constructor ,React Updates , render , componentDidMount , componentWillUnmount .

 ## What does componentDidMount do?
   > This is where you run statements that requires that the component is already placed in the DOM.


[♥️from](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

  ![lifecycle](../img/0_0saPKFiTUk6W3FYp.png)


<br><hr><br>


# Props 🆚 State

 ## What types of things can you pass in the props?
   >  The values can be any data type, from strings to functions, objects, etc.
 
 ## What is the big difference between props and state?
   * state 
    > It is something like attributes in OOP and it's be local to a class.
  * props
    > like parameters - they are **passed** to a component **(from the parent)**.
 
 ## When do we re-render our application?
   > React components automatically re-render whenever there is a change in their state or props.
 
 ## What are some examples of things that we could store in state?
  > some data like you want to change or update in your application.

[♥️from](https://www.youtube.com/watch?v=IYvD9oBCuJI)

[♥️from](https://www.educative.io/edpresso/how-to-force-a-react-component-to-re-render)

[♥️from](https://dev.to/maasak/passing-props-in-react-3ngh#:~:text=What%20Are%20Props%3F,to%20functions%2C%20objects%2C%20etc.)


  >   ![Props vs State](https://i.stack.imgur.com/wqvF2.png)
  >   ![Props vs State](https://i.ytimg.com/vi/aLmwln09Tbs/maxresdefault.jpg)

### Props
   *  passed into the component(not inside).
   * render dynamic data.
   * dealing with title and subtitle.

### State 
   * inside the component.
   * not deling with dynamic data.
   * not deling with title and subtitle.
   * What does setState do? 
        * setState() schedules an update to a component’s state object. When state changes, the component responds by re-rendering.


 

   #### React Bootstrap
    * React-Bootstrap replaces the code to react components,without unneeded dependencies and that givs us more countrol with the component.



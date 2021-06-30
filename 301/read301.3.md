![react](https://miro.medium.com/max/2128/1*KN7zbaWkbm5E71zZWfTf7A.gif)
# Passing Functions to Components 
 ## How do I pass an event handler (like onClick) to a component?  [♥️from](https://reactjs.org/docs/faq-functions.html)
  > Like `<button onClick={this.handleClick}>` then we need create a function in the class (📍 globle).
  > ` handleClick() {`
   ` console.log('Click happened');`
  `}`


# Lists and Keys 
  ## 🗺️ map : Array.prototype.map()  
   >  The map() method creates a new array populated with the results of calling a provided function on every element in the calling array. [♥️from](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map) 
   >  returns a map object of the results after applying the given function to each item 
   ![map](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSNRAhYVJ0WYW-YMrJ6b1q1iXxmhsJxNcv-9A&usqp=CAU)
  
  * What does .map() return?⬇️
  *  **map** method similar with as **forEach** but map **need return**.
  ## Object.keys(👁️obj) 
  *  is a built-in JavaScript method that returns an array of the given object’s property names.
  * The **👁️obj** parameter is required, and its properties are to be returned.
  * The return value is an array of **strings**.

  *  Each list item needs a unique __a key__.

  * What is the purpose of a key? to make different between the items,help React identify which items have changed.

# The Spread Operator ...
  * What is the spread operator?
   > is a new addition to the set of operators in ES6. It takes in an iterable (e.g an array) and expands it into individual elements.

  * List 4 things that the spread operator can do?
   > allows an iterable to expand in places, use in the variable array where there is more than 1 value are expected, makes the code concise and readability,. It allows us the privilege to obtain a list of parameters from an array.

  * Give an example of using the spread operator to combine two arrays?
   > like:`const arr3 = [...arr1, ...arr2] //arr3 ==> [1,2,3,4,5,6]`
  * 
   > `sum(...numbers)` will retarn the sumation of the array like: [1, 2, 3] ➡️  6

  * Give an example of using the spread operator to combine two objects into one.
   >  `let person = {`
   `  firstName: 'moh',`
   `   lastName: 'omar',`
   `};`
   `let job = {`
   ` jobTitle: 'JavaScript Developer',`
   `  location: 'JO'`
   `};`
   `let employee = {`
   `  ...person,`
   `   ...job`
   `};` 
   > the Output : will be all elemint in one object.


  * The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.[♥️from](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab) 
  ![ Spread Operator](https://miro.medium.com/max/1000/1*oB0L8ezFrNnU9aR55BrEng.png)

# Pass Functions 

  ### In the video, what is the first step that the developer does to pass functions between components?
   * create the function where the state is.
  ### In your own words, what does the increment function do?
   * update the state value by adding 1 or something else.
  ### How can you pass a method from a parent component into a child component?
   * like this in the parent page (in the component(child) tage `<>` )
    > `onChange={this.handleChange}`
  ### How does the child component invoke a method that was passed to it from a parent component?
   * by this.props.onChange()
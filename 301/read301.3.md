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

  *  **map** method similar with as **forEach** but map **need return**.
  ## Object.keys(👁️obj) 
  *  is a built-in JavaScript method that returns an array of the given object’s property names.
  * The **👁️obj** parameter is required, and its properties are to be returned.
  * The return value is an array of **strings**.
  *  Each list item needs a unique __a key__.
  * What is the purpose of a key? to make different between the items,help React identify which items have changed.

## The Spread Operator ...
  * rest parameters ...
  * The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.[♥️from](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab) 
  ![ Spread Operator](https://miro.medium.com/max/1000/1*oB0L8ezFrNnU9aR55BrEng.png)


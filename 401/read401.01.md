# Node Ecosystem, TDD, CI/CD

![.map](https://i0.wp.com/css-tricks.com/wp-content/uploads/2019/03/arrays-map.png?fit=1200%2C600&ssl=1)

## Array.map()

- .map() is a method used with arrays. it _create new array_ filled from the result .
- .map() used the original array to run the code _over each element_(we can use the element or updated) of the original array to create a new one, as we say.
- Must use _return_ in .maP() code .
- The new array should be the _same length_ as the original.

### Parameters :

1. callbackFn
2. element
3. index (Optional)
4. array (Optional)
5. thisArg (Optional)

- Return value

### LIKE

`let numbers = [1, 4, 9]`
`let roots = numbers.map(function(num) {`
` return Math.sqrt(num)`
`})`

![.reduce](https://i2.wp.com/css-tricks.com/wp-content/uploads/2019/03/arrays-03.png?ssl=1)

## Array.reduce()

- .reduce is a method used with arrays. don't affect the original array.
- .reduce used the original array to run the code over each element(find the summation to the array) of the original array.

### Parameters :

1. callbackFn
2. accumulator
3. currentValue

4. index (Optional)
5. array (Optional)
6. initialValue (Optional)

- Return value

### LIKE

`[0, 1, 2, 3, 4].reduce((accumulator, currentValue, currentIndex, array) => {`
`return accumulator + currentValue`
`}, 10)`

## superagent()

- With async / await syntax
  ![ async / await ](/img/C-superagent.1.PNG)

- With normal Promise .then() syntax
  ![ .then ](/img/C-superagent.2.PNG)

## promises

- JS does the code synchronously (step by step), if there is a block that will take time the JS will not do it in order but will promise it back when it is finished.

## Are all callback functions considered to be Asynchronous? Why or Why Not?

- not all of them, just when we use (.then or async / await)

[mdn](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

[code](https://replit.com/@Mohammadatta/AsyncAwait#index.js)


# Understanding the JavaScript Call Stack

 ## What is a ‘call’❓
  > The **call** stack is primarily used for function invocation **(call)**. Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. 
  > The **call** stack is synchronous.

 ## How many ‘calls’ can happen at once❓
   >  Is done, one at a time

 ## What does LIFO mean❓
  >  **(Last In, First Out)**.
  >  LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

 ## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.❓
   > ` function firstFunction(){`
     >  ` console.log("Hello from firstFunction");  }`
 
   > `function secondFunction(){ `
      > `firstFunction();`
      >`console.log("The end from secondFunction");   }`

   > `secondFunction();`

 ## What causes a Stack Overflow❓

  > A stack overflow occurs when there is a **recursive function** (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

   * a recursive function 
   * Infinite recursion
   * Very deep recursion
   * Very large stack variables


# JavaScript error messages
   
  > 😂😂😂
  ![error](https://media.tenor.com/images/f7b614ad76695f3310ad55f4e3c3c110/tenor.gif)
  
 ## What is a ‘refrence error’❓
 > This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

 ## What is a ‘syntax error’❓
 >  this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

 ## What is a ‘range error’❓
 > Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.


 ## What is a ‘tyep error’❓
 > These types of errors show up when the types (number, string, ..) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

 ## What is a breakpoint❓
 > At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).



>  **Debugging** >>> open your page with your JS code
    > (press cmd+o in macOS or Ctrl+o in Windows) 
    > choose your file to debug, click the line you wanna debug
    >  refresh your page again (F5).

 ## What does the word ‘debugger’ do in your code❓
 >  the easiest and maybe the most common way its to simply console.log() the variables you want to check or, by using chrome developer tools 



[♥️from](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/) <hr>
 [♥️from](https://en.wikipedia.org/wiki/Stack_overflow)

<hr><br><hr>

[♥️from](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c) <hr>
 [♥️from](https://www.w3schools.com/js/js_debugging.asp#:~:text=At%20each%20breakpoint%2C%20JavaScript%20will,typically%20with%20a%20play%20button)
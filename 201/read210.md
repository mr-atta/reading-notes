# Error Handling & Debugging

#### To find the source of an error, it helps when you know how scripts are working.

![error](https://learningactors.com/wp-content/uploads/2018/05/error_handling.jpg)

- the scripts maybe are complex, but we can keep track of the code line by line (The code is executed line by line).
- If there is a call to a function, the interpreter should go to the function and do it back to his place and continue the code.
- The JavaScript interpreter uses the concept of _execution contexts_. There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope.
- Every statement in a script lives in one of three execution contexts:

  1.  **GLOBAL CONTEXT**

  - Code that is in the script, but not in a function.
  - There is only one global context in any page.

  2.  **EVAL CONTEXT** (NOT SHOWN)

  - Text is executed like code in an internal function, **called eval**

  3.  **GLOBAL SCOPE**

  - VARIABLE SCOPE - If a variable is declared outside a function, it can be used anywhere because it has global scope. - When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.
    ![SCOPE](https://miro.medium.com/max/1052/1*2oAKZtsRSn_vWfJeHHWwYQ.png)

## The Stack

- when a ststement has to call some other code in order to do its job,the new task goes to the top of the pile of things to do.
- once the new task has been performed, the interpreter can go back to the task in hand.
- Each time a new item is added to the stack , it creates a new execution context.
- If the function get called a second time, the variables can have different values.

#### Each time a script enters a new execution context, there are two phases of activity:

> ![js](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRQEfbwTKlHyEEG-M21y-dKKEWMxN8m7TfwYw&usqp=CAU)

1. PREPARE

- The new scope is created
- Variables, functions, and arguments are created
- The value of the this keyword is determined

2. EXECUTE

- Assign values to variables
- Reference functions and run their code
- Execute statements

#### UNDERSTANDING ERRORS

- If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.
- If you are anticipating that something in your code may cause an error, you can use a set of statements to **handle the error**

#### ERROR OBJECTS

- Error objects can help you find where your mistakes are and browsers have tools to help you read them.

  > ![ERROR OBJECTS](https://i.stack.imgur.com/QnUPb.png)

- Syntax Error ,SYNTAX IS NOT CORRECT
- Ref erenceError ,VARIABLE DOES NOT EXIST
- EvalError ,INCORRECT USE OF eval() FUNCTION
- URI Error ,INCORRECT USE OF URI FUNCTIONS
- Type Error ,NUMBER OUTSIDE OF RANGE
- RangeError ,VALUE IS UNEXPECTED DATA TYPE
- Error ,GENERIC ERROR OBJECT
- NaN ,NOT AN ERROR

### HOW TO DEAL WITH ERRORS

- DEBUG THE SCRIPT TO FIX ERRORS
- HANDLE ERRORS GRACEFULLY

### SUMMARY

- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
- Debugging is the process of finding errors. It involves a process of deduction.
- The console helps narrow down the area in which the error is located, so you can try to find the exact error.
- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.

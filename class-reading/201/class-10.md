## Chapter 10 - 'Debugging'

### Order of executio.
to fin the source of your error you first need to understand in what order your code is being processed and handled. this helps to determine at what stage of of execution your code is throwing an error and makes tracking down the error much more targeted. 

### Execution Contexts
Every statement in a script lives in one of three execution contexts
1. Global context: code that lives for the whole script.
2. Function context: code that is being run within a function.
3. Eval Context: text executed in an internal function. 

### Variable Scope
1. Global Scope: Exactly what it sounds like, variables that are declared outside the scope of a function and are accessed by all code.
2. Function-level scope: variables declared within the scope of a function are accesed only by the function and exist only within that function.

### The stack 
- javaScript handles and interperetes one line of code at a time. when a statement needs data from another function, it **Stacks** the new function on op of the current task.

We check for errors using the power of Dev. Tools within our browser. 
-> we use console.log() to post our code to the console to make sure we are getting the expected value back.
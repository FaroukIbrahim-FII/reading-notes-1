# Read: 10 - JS Debugging

# JAVASCRIPT :

#### JavaScript provides ways to deal with errors within the code or deal with expected errors, you will not always be able to write 100% clean code, as these methods help to make the code better and avoid some errors.

#### When a function is called inside another function, the work of the first function is stopped, the called function is executed, and then when the called function is terminated, the first function completes the work.


#### When defining a variable in the global, this is called the global scope and it can be used anywhere, but when declaring the variable inside a function this is called local scope and it is only used inside this function.

### ERROR OBJECTS : Error objects can help you find where your mistakes are and browsers have tools to help you read them. It will return information on : name ,message ,fileNumber , lineNumber. Ex : Error ,Syntax Error ,ReferenceError ,TypeError ,Range Error ,URI Error ,EvalError.

### TWO WAYS TO DEAL TO DEAL WITH ERRORS :
* DEBUG THE SCRIPT TO FIX ERRORS : With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing. 
* HANDLE ERRORS GRACEFULLY : You can handle errors gracefully using try, catch, throw, and finally statements.

### The Console object provides access to the browser's debugging console. `console.log()`, `console.info()` , `console.warn()` , `console.error()` , `console. group()` , `console.groupEnd()` , `console.assert()` .

### BREAKPOINTS : You can pause the execution of a script on any  line using breakpoints. Then you can check the  values stored in variables at that point in time. 

### HANDLING EXCEPTIONS : Errors Will Happen, When executing JavaScript code, different errors can occur ,Errors can be coding errors made by the programmer, errors due to wrong input, and other unforeseeable things.
* try : statement allows you to define a block of code to be tested for errors while it is being executed.
* catch : statement allows you to define a block of code to be executed, if an error occurs in the try block.
* finally : statement lets you execute code, after try and catch, regardless of the result.

```JAVASCRIPT
    try { 
        // Try to execute this code 
    }catch (exception) { 
        // If there is an exception run this code 
    }finally { 
        // This always gets executed
    }
```

[ Back To README !]( https://yousefabujalboush.github.io/reading-notes/ )
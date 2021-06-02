#  the Duckett JS book:

## JavaScript book, Ch. 10, “Error Handling & Debugging”

## the stack:

***the js interpreter processes one line of code at time when a ststement needs datd from amother function, it stacks (or piles) the new function on top of the current tast***

### EXECUTION CONTEXT & HOISTING
***Each time a script enters a new execution context, there are two phases of activity:***
1. PREPARE
2. EXECUTE

### UNDERSTANDING SCOPE

***In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object.***

### UNDERSTANDING ERRORS 

***If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.***

### HOW TO DEAL WITH ERRORS

***there are two things you can do with the errors. ***

1. DEBUG THE SCRIPT TO FIX ERRORS

2. HANDLE ERRORS GRACEFULLY





### summary error handling and debugging:

- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code. 

- Debugging is the process of finding errors. It involves a process of deduction. 

- The console helps narrow down the area in  which the error is located, so you can try to find the exact error. 

- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. 

- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback. 



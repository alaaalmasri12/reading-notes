# Error Handling & Debugging
we use multiple things for debugging like
-the console & dev tools
-common problem
-Handling errors
### ORDER OF EXECUTION
to find source of an error you have to know how script is executed some tasks can not be completed unsless theres functions or stamtnets that has been run

>javascript interubter uses the concept of execution context
what is an execution contentex?
A)every statment in script lives in one or there execution context
Globel-context:code runs in javascript not in a function every page has one globel-context
function-contet:code runs inside a function each function is own function has its own functional context
eval function:its a build in function eval()
the javascript interupter procssess a single line code at time
### UNDERSTANDING ERRORS 
If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code
types of errors
-Syntax Error :SYNTAX IS NOT CORRECT 
-Refrence Error:VARIABLE DOES NOT EXIST 
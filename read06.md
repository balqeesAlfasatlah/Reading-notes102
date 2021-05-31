# Fuction in javascript 

## control flow

The **control flow **is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 

## function

** function** is a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.


### Defining functions
Function declarations
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

1. The name of the function.
2. A list of parameters to the function, enclosed in  parentheses and separated by commas.
3. The JavaScript statements that define the function, enclosed in curly brackets, {...}.

### Calling functions
Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.

**here full example :**

function myFunc(theObject) {
  theObject.make = 'Toyota';
}

var mycar = {make: 'Honda', model: 'Accord', year: 1998};
var x, y;

x = mycar.make; 

myFunc(mycar);
y = mycar.make; 


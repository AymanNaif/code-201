# JavaScript (Chapter 10: Error Handling & Debugging)


JavaScript can be hard to learn and everyone makes 
mistakes when writing it. We  will help you learn 
how to find the errors in your code. and teach you how 
to write scripts that deal with potential errors gracefully



The Stack :

The javascript interpreter proocesses one line of code at a time .
When a statment needs data from another function , it stacks(or piles)
the new function on top of the current task .


Execution Context & Hoisting :

Each time a script enters a new execution context, there are two phases 
of activity: 


1- Prepare .

- The new scope is created 
- Variables, functions, and arguments are created 
- The value of the this keyword is determined 


2- Execute . 



- Now it can assign values to variables 
- Reference functions and run their code 
- Execute statements 


Understanding Scope :


In the interpreter, each execution context has its own `variables` object. 
It holds the variables, functions, and parameters available within it. 
Each execution context can also access its parent's `variables` object


Understanding Errors :

If a JavaScript statement generates an error, then it throws an exception. 
At that point, the interpreter stops and looks for exception-handl ing code. 

## ERROR OBJECTS
Error objects can help you find where your mistakes are and browsers have tools to help you read them.

When an Er ror object is created, it will contain the following properties:

<<<>>>..............................

There are seven types of built-in error objects in JavaScript. You'll see them on the next two pages:

<<<<>>>>>>>>>>>>>>>>>>>>>>>>>>>

## RROR OBJECTS CONTINUED

<<<<<<<<<<<<<<<>>>>>>>>>>>>>>>


These two pages show JavaScript's seven different types of error objects and some common examples of the kinds of errors
you are likely to see. As you can tell, the errors shown by the browsers can be rather cryptic.

<<<>>>>>>>>>

## HOW TO DEAL WITH ERRORS

1. DEBUG THE SCRIPT TO FIX ERRORS If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it.

2. HANDLE ERRORS GRACEFULLY You can handle errors gracefully using try, catch, throw, and f i na 1 ly statements.


# A DEBUGGING WORKFLOW

Debugging is about deduction: eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be, then look for clues.

### WHERE IS THE PROBLEM?
First, should try to can narrow down the area where
the problem seems to be. In a long script, this is
especially important.
1. Look at the error message, it tells you:
The relevant script that caused the problem.
The line number where it became a problem for
the interpreter. (As you will see, the cause of
the error may be earlier in a script; but this is the
point at which the script could not continue.)
The type of error (although the underlying cause
of the error may be different).
2. Check how far the script is running.
Use tools to write messages to the console to tell
how far your script has executed.
3. Use breakpoints where things are going wrong.
They let you pause execution and inspect the va lues
that are stored in variables.

### WHAT EXACTLY IS THE PROBLEM?
Once you think that you might know the rough area
in which your problem is located, you can then try to
find the actual line of code that is causing the error.
1. When you have set breakpoints, you can see if the
variables around them have the values you would
expect them to. If not, look earlier in the script.
2. Break down I break out parts of the code to test
smaller pieces of the functionality.
Write values of variables into the console.
Calrfunctions from the console to check if they
are returning what you would expect them to.
â€¢ Check if objects exist and have the methods I
properties that you think they do.
3. Check the number of parameters for a function, or
the number of items in an array.
And be prepared to repeat the whole process if the
above solved one error just to uncover another ...


### CONDITIONAL
#### BREAKPOINTS

We can indicate that a breakpoint should be
triggered only if a condition that we specify is
met. The condition can use existing variables


If we know our code might fail, use try, catch, and finally.
Each one is given its own code block.

#### THROWING ERRORS

If we know something might cause a problem for our script, we can
generate our own errors before the interpreter creates them.

To create our own error, we use the following line:

throw new Error( 'message'
);


#### DEBUGGING TIPS

* ANOTHER BROWSER
* ADD NUMBERS
* STRIP IT BACK
* SEARCH
* CODE PLAYGROUNDS
* VALIDATION TOOLS
* EXPLAINING THE CODE

# JavaScript
## Chapter 1: The ABC of Programming
#### A script is a series of instructions that a computer can follow to achieve a goal, To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.
### How to achieve our goals ?
#### at first you need to start with the big picture of what you want to achieve, and break that down into smaller steps.
1. #### DEFINE THE GOAL : you need to define the task you want to achieve.
2. #### DESIGN THE SCRIPT : To design a script you split the goal out into a series of tasks that are going to be involved in solving this puzzle.
3. #### CODE EACH STEP : Each of the steps needs to be written in a programming language that the computer understands. In our case, this is JavaScript.


## How javascript makes web pages more interactive :
1. ACCESS CONTENT:You can use JavaScript to select any element, attribute, or text from anHTML page.
2. MODIFY CONTENT: You can use JavaScript to add elements, attributes, and text to the page, or remove them. 
3. PROGRAM RULES: You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page.
4. REACT TO EVENTS: You can specify that a script should run when a specific event has occurred.

## WRITING A SCRIPT
To write a script, you need to first
state your goal and then list the
tasks that need to be completed in
order to achieve it. 
Start with the big picture of what
you want to achieve, and break
that down into smaller steps. 
1. DEFINE THE GOAL: First, you need to define the task you want to achieve. You can think of this as a puzzle for the computer to solve. 
2. DESIGN THE SCRIPT: To design a script you split the goal out into a series of tasks that are going to be involved in solving this puzzle. This can be represented using a flowchart. 
3. CODE EACH STEP: Each of the steps needs to be written in a programming language that the computer understands. In our case, this is JavaScript. 

## EXPRESSIONS
An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions. 
1. EXPRESSIONS THAT JUST ASSIGN A
VALUE TO A VARIABLE Example :

var color = 'beige'; 

2. EXPRESSIONS THAT USE TWO OR
MORE VALUES TO RETURN A
SINGLE VALUE  EXAMPLE : 

var area = 3 * 2; 

## OPERATORS
Expressions rely on things called operators; they allow programmers to create a single value from one or more values. 

## ARITHMETIC OPERATORS
JavaScript contains the following mathematical operators, which you can use with numbers.  You may remember some from math class.
![1](https://www12.0zz0.com/2021/02/24/20/173755262.png)

## Functions
Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedureâ€”a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by: 

* The name of the function.

* A list of parameters to the function, enclosed in parentheses and separated by commas.
* The JavaScript statements that define the function, enclosed in curly brackets, {...}.

For example :
 
![2](https://www12.0zz0.com/2021/02/24/20/327343693.png)


### COMPUTERS CREATE MODELS OF THE WORLD USING DATA
#### programmers create a very different kind of model, especially for computers. Programmers make these models using data. That is not as strange or as scary as it sounds because the data is all the computer needs in order to follow the instructions you give it to carry out its tasks.

### OBJECTS & PROPERTIES
#### OBJECTS : In computer programming, each physica l thing in the world can be represented as an object. There are two different types of objects here: a hotel and a car.
#### In computer programming, each physica l thing in the world can be represented as an object. There are two different types of objects here: a hotel and a car. Each object can have its own( Properties, Events, Methods) Together they create a working model of that object.
#### PROPERTIES :Each property has a name and a value, and each of these name/value pairs tells you something about each individual instance of the object.

### EVENTS
#### There are common ways in which people interact with each type of object. 
#### Programmers choose which events they respond to. When a specific event happens, that event can be used to trigger a specific section of the code. Scripts often use different events to trigger different types of functionality. So a script will state which events the programmer wants to respond to, and what part of the script should be run when each of those events occur.

### METHODS

Methods represent things people need to do with objects. They can
retrieve or update the values of an object's properties.

WHAT IS A METHOD?
Methods typically represent how people (or otherthings) interact with an object in the real world.
They are like questions and instructions that:
â€¢ Tell you something about that object (using
information stored in its properties)
â€¢ Change the value of one or more of that object's
properties

WHAT DOES A METHOD DO?
The code for a method can contain lots of instructions that together represent one task.
When you use a method, you do not always need to know how it achieves its task; you just need to know
how to ask the question and how to interpret any answers it gives you.

PUTTING IT ALL TOGETHER

Computers use data to create models of things in the real world.
The events, methods, and properties of an object all relate to each other:
Events can trigger methods, and methods can retrieve or update an
object's properties.

### WEB BROWSERS ARE PROGRAMS BUILT USING OBJECTS

WINDOW OBJECT
On the right-hand page you can see a model of a computer with a browser open on the screen.
The browser represents each window or tab using a window object. The location property of the window
object will tell you the URL of the current page

DOCUMENT OBJECT
The current web page loaded into each window is modelled using a document object.
The title property of the document object tells you what is between the opening `<t; t le>` and closing
`</title>` tag for that web page, and the lastModified property of the document object
tells you the date this page was last updated.

### THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE

Using the document object, you can access and change what content
users see on the page and respond to how they interact with it.

Like other objects that represent real-world things, the document object has:

PROPERTIES
Properties describe characteristics of the current web page (such as the t itle of the page).

METHODS
Methods perform tasks associated with the document currently loaded in the browser (such
as getting information from a specified element or adding new content).

EVENTS
You can respond to events, such as a user clicking or tapping on an element.

### HOW A BROWSER SEES A WEB PAGE

In order to understand how you can change the content of an HTML
page using JavaScript, you need to know how a browser interprets the HTML code and applies styling to it.

1: RECEIVE A PAGE AS HTML CODE Each page on a website can be seen as a separate document .
So, the web consists of many sites, each made up of one or more documents.

2: CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY The model shown on the right hand page is a representation
of one very basic page. Its structure is reminiscent of a family tree. At the top of the model is a document object,
which represents the whole document. Beneath the document object each box is called a node. Each of these nodes is
another object. This example features three types of nodes representing elements, text within the elements, and attribute.

3: USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN If there is no CSS, the rendering engine will apply default styles
to HTML elements. However, the HTML code for this example links to a CSS style sheet, so the browser requests that file and
displays the page accordingly. When the browser receives CSS rules, the rendering engine processes them and applies
each rule to its corresponding elements. This is how the browser positions the elements in the correct place, with the
right colors, fonts, and so on.

### HOW DO I WRITE A SCRIPT FOR AWEB PAGE ?

HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER

HTML ONLY
Starting with the HTML layer allows you to focus on the most important thing about your site:
its content. Being plain HTML, this layer should work on all kinds of
devices, be accessible to all users, and load quite quickly on
slow connections.

HTML+CSS
Adding the CSS rules in a separate file keeps rules regarding how the page looks
away from the content itself. You can use the same style sheet
with all of your site, making your sites faster to load and easier to maintain.
 Or you can use different style sheets with the same content to create different views of the same data.

HTML+CSS+JAVASCRIPT
The JavaScript is added last and enhances the usability of the page or the experience of
interacting with the site.
Keeping it separate means that the page still works if the user cannot load or run the
JavaScript. You can also reuse the code on several pages (making the site faster to load and easier to maintain).

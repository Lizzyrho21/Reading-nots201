## Javascript Reading-notes

Out of everything we've learned, lets focus on what we *really* need to know..

- Variables
We use Variables to define what we want Javascript to run

EX. 
var = x;
var = 32;
let = "32";

We can either have the variable we define equal an integer, an object, or a string(piece of code).

- Comments
We use comments in JS to communicate with the developer what piece of code does what and why. The computer and the user interacting with the page will not see the comment.

Here are two types of comments:

// this is a single-line comment.

/* This is where a multi-line comment is placed. It is used for long sentences! */

- Loops
Loops are used to run a certain block of code over and over again.
Here is an example of a loop.

-for loop
A for loop is used when we know exactly how many times we want the loop to run.
Here is an example:
for(var i = 0; i < 10; i++) {
    console.log(i);
}

Lets break this code apart. 1. A variable i is defined first, then an argument 'if i is less than 10 is declared. After that, the i++ is declared. This means that for every loop that is less than 10, the increment will increase by 1!
inside the brackets, we placed a console.log(i) to check our code in the console.

Using Arrays

An array is a special type of variable that stores a list of values.

You can use arrays when make a list of related items.

EX. 
var food;
food = ['eggs', 'chicken', 'steak'];

You can also store Arrays like this Example:

new Array('eggs', 'chicken', 'steak');

- You can number and access the items in an array!

EX.

Counting the numbers in an array starts with 0. So for example,

var car = ['Honda', 'Volvo', 'Sentra']; <---- This would be counted 0, 1, 2.


Using if statements:

The if statement evaluates a condition. if the condition is true, a block of code will run, either with another block of code or a message. If it is not true, the code will not run.

EX. 

if (score >= 50) {
    passed();
}

- Switch statements start with a variable called a switch value.


switch(x) {
    case'one':
    title = 'stage 1';

    case 'two':
    title = 'stage 2';

    case 'three':
    title = 'stage 3';

    default:
    title = 'Test';
    break;

}

In the example above, if the case is in stage one, the code will run and break if it makes it to stage two. When stage two is run, that will break onto stage 3. 
It is similar to making a video game. if you were to win a round, there might be message sent to you that pushes you toward the next round!



- Functions & Methods, Objects & Built in objects

 **Functions and Methods**
- Funcs are a series of statements that have been grouped together because they perform a specific task!

- Method is the same as a function except methods are created inside and are apart of an object!

- Objects are used to create models of the world usins data and are made up of properties and methods.

- Built-in Objects
The browser comes with a set of objects that act like a toolkit for creating interactive web pages.

Lets dive deep!

## More about functions!

Grouping together the statements that are required to answer a question or perform a task helps organize code!

The statements in a function are not always executed when a page loads, so functions also offer a way to *store* the steps needed to achieve a task. The script can then ask the function to perform all of those steps as and when they are required. To do this, you need to give the function a name, and then call (or ask) it to perform the function when you are ready.

* Declaring a function 

1. To create a function, you need to *give it a name* and then write statements **needed to achieve the task inside the curly braces.**

EX. 
function sayHello( ) {
    document.write("Hello!");
}

// **IMPORTANT**
// It is imperative to remember that functions store the code required to perform a specfiic task, and the script can ask the function to perform that task when needed!

*Calling a function*

1. To run the code in the function, you use the function name followed by parenthesis.

2. You can call the same function as many times as you want within the same JS file!!

## Declaring functions that need information ....

---
When a function needs specific information to perform its task you can most likey use parameters within the parenthesis. The parameters act like variables.

EX.

function getArea(width, height){
    return width * height;
}
--
The function above will calculate and return the area of a rectangle. to do this, it needs the rectangle's width and height. Each time you call the function these values can be different!


- This demonstrates how the code can perform a task without knowing the exact details in advanced, as long as it has **rules** it can follow to achieve the task!

- When you deisgn a script, you need to note the information the function will requirs in order to perorm it's task


## Calling functions that need information

When you call a function that has parameters, you speciy the values it should use in the parenthesis that follow it's name. The values are called arguments, and they can be provided as values or variables!

1. Arguments as variables
- When the function beloew is called, the first number is used for the width, the second is used for height. 
getArea(3, 5);


2. Arguements as variables
- You do not have to specify actual values when calling a function - you can use variables in thier place. So the following does the *same thing*

wallWidth = 3;
wallHeight = 5;
getArea(wallWidth, wallHeight);


## Parameters vs Arguments
Parameters are declared in functions
Arguments are put in place to call the function!

Happy coding!









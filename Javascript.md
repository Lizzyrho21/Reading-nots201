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

happy coding!


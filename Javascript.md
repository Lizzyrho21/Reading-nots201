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
There are two types of Loops:

-for loop
A for loop is used when we know exactly how many times we want the loop to run.
Here is an example:
for(var i = 0; i < 10; i++) {
    console.log(i);
}

Lets break this code apart. 1. A variable i is defined first, then an argument 'if i is less than 10 is declared. After that, the i++ is declared. This means that for every loop that is less than 10, the increment will increase by 1!
inside the brackets, we placed a console.log(i) to check our code in the console.

- while loop
A while loop is used when we do not know how many times a block of code will execute.
while (i < 10) {
  text += "The number is " + i;
  i++;
}

Happy Coding! 
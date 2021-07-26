
## Object Literals

What is an object?

Objects group together a set of variables and functions to create a model of something rom reality


To create an object, we use literal notation.

EX.
Properties entered:
'''
var hotel = {
name = ‘Quay’,
Rooms = 40.
Booked = 25,

Method :checkAvailability: function( ) {
return this.rooms - this.booked;
}
'''
In this method above, the ‘.this’ keyword is used to indicate that it is using the rooms and cooked properties of this object!

When using properties, treat the values like you would do or variables: strings live in quotes and arrays like in square brackets.


### Accessing an object and dot notation

To access a property or method of an object, you use the name of the object followed by a period and the name of the property or method you want to access.
This is called dot notation. 

The ‘.’ Or period is known as the member operator.

 * This notation is used when 
 The name of the property or method contains special characters (such as a dash)

# The DOM or Document Object Model

Javascript makes the HTML page active and dynamic via the DOM

Javascript communicates with the properties, methods and events in the interface called the Document Object Model, or DOM.

The DOM is a tree-like representation of the web page that gets loaded into the browser.

It represents the web page using a series of objects. The main object is the document object, which in turn houses other objects which also house their own objects and so on.

It **models** an HTML page.

There are 4 types of nodes in a DOM:

1. Document Node
Represents the entire page of the HTML document and corresponds to the document object. It is the starting point for all other nodes

2. Element node
HTML elements describes the structure of an HMTL page. 

3. Attribute nodes
The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree

4. Text nodes 
 Once you have accessed an element node, you can then reach the text within the element. This is store into its own text node.

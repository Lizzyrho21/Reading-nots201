## HTML Chapter 2: “TEXT” Reading notes Cheatsheet

There are two types of markup:

- Structural Markup
- Semantic Markup

* Structural markup

A. Headings

There are the 6 types of headings.

- <h1>
- <h2>
- <h3>
- <h4>
- <h5>
- <h6>

Result:

- # This is an h1 heading.
- ## This is an h2 heading.
- ### This is an h3 heading.
- #### This is an h4 heading.
- ##### This is an h5 heading.
- ###### This is an h6 heading.

B. Paragraphs
The <p> opening and closing tag gives us a paragraph

<p> Hello World! </p>

results to:
Hello World!

C. Bold and Italic

- The <b> tag makes our letters bold.
  <b> Hello World! </b>
  results to:
  **Hello World!**

- The < i > tag makes our letters italic.
  < i > Hello there! < i >,
  results to:
  _Hello there!_

  2.  Semantic HTML
      Here are some examples of Semantic HTML.

  A. The < strong > tag places emphasis on paragraphs.

  Don't < strong >ever</ strong > get too close to a blackbear!

  results to :
  Don't **ever** get too close to a black bear!

  B. the < em > tag places empahasis on paragraphs.

  You didn't < em > have < / em > to come.

  results to:
  You didn't _have_ to come.

  B. the < s > tag strikes out a piece of text that is not accurate but no irrelavant.
  < s > Was $995 < s >

  results to:
  ~~was $995~~

  - HTML lists
    There are 3 types of HTML lists:
  - Unordered
  - Ordered
  - Definition

  - Unordered list give us bulletpoint lists. the syntax is as follows:
  <ul>
   <li>fish</li>
   <li>corn </li>
   <li>Salad </li>
   </ul>

  - Ordered lists gives us numbered lists, the syntax is as follows
  <ol>
  <li>Flour</li>
  <li>Butter</li>
  <li>Eggs</li>
  </ol>

  - Definition
    -Definition gives us a formatted definiton under our defined item. The syntax looks like the following:


      <dl>
      <dt>Siamese</dt>
      <dd>Siames cats typcally have white and black/brownish ur with big ears and smaller eyes</dd>


      </dl>


      -----

      ## HTML layout

      HTML are very useful in structuring our HTML document and with CSS styling. Let's take a closer look.

      To start off, there are two important terms you need to know:

      1. Block-level elements are elements that start on a new line when typed. Sort of like this one! This is the defualt HTML positioning.

      2. Inline elements, on the other hand, flow in between surround text. Examples of these elements are < img >, < b >, and < i >.

      Both of these elements are treated like boxes in an html element. **Remember them!**

  ## Positioning schemes

  We use positioning schemes to control the layout of a page. Here are the ones you should know for now:
<dl>
  <dt>- Normal flow</dt>

  <dd>This is the default positioning for block-level elements we mentioned before! Each item starts on a new line regardless if it takes up a page or not.</dd>
  <dl>

   <dt>Relative positoning</dt>
    <dd>This moves an elements from the normal flow to whichever place we want it to be from there. It moves on its own and does not affect the others</dd>

  <dl>
  <dt>Absolute positoning</dt>

  <dd>his positions the element in relation to its containg element. So it will move depending on where it is from the parent element! It is taken out o the normal flow and does not affect the positioning of the others. Its the odd one out!</dd>
  </dt>
  
    <dl>  Fixed positioning</dl>
    
    <dl>

   This is a form of absolute positioning!

    <dd>It positions the element in relatin to the browser window instead of in the parent container (This is the wierdest one!) However, it still does not affect the positioning of the others.</dd>
    </dl>


<dl>
 <dt> Floating elements</dt>
<dd>
  Aha! floating elements do affect the positioning of the other elements. it can either float left, right, up, or down and change the other elements to be beside whereever it is.
  </dd>

</dl>

REMEMBER THIS!


HTML links

- Links are creating using the < a > href element!

EX. 
< a href = "URL">This takes you to my page!!</ a>

Inside of the a link is the copy of the URL you want to take the user to. Inside of the opening and closing brackets is the text that will show up on the web page. 

**This example is for if you want to link to other active webpages!**

----
To link to other pages of the website, you need to link to the file that is inside of your folder! 

< a href = "index.html" >Homepage< a >

The same element is used here but the url is now an index.html file that takes you back to the main html page. you will need to make sure it is saved inside of the file you are working on so it knows which HTML file it needs to be in!! 


## Structure
---
On larger webpages, make sure to organize your code so you know where it is and how to acess it!

In a webpage, there is structure, relationships, and homepages to further organize code and use it to make navigation easier for the user and developers working on the page. This is also known as using a family tree. Which we will get into more a little later. 

Happy coding!!
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
  You didn't *have* to come.

  B.  the < s > tag strikes out a piece of text that is not accurate but no irrelavant.
   < s > Was $995 < s >

   results to:
   ~~was $995~~


   

   

## CSS notes
Welcome to my CSS notes!

1. What is CSS??
-CSS or (Cascading Style Sheets) is a language used to style document’s layout. All the colors, text styles, and animations that you might see on a website are thanks to the help of mostly CSS. It gives us the tools we need to make a site **POP**.

2. What is the Syntax?
-CSS syntax is  *alot* different than HTML. While HTML has tags that look like this ‘<content>’ Css has opening and closing brackets like this : ‘{content}’ . At the beginning, before the first bracket, there must be a **selector** that starts the syntax.

- A **Selector** is the HTML element we want to style. This could be a ‘h1’, ‘h2’, ‘nav’, etc.
- A declarations is then put inside the curly brackets to create a style for the element. For example, if we had an h1 element and we wanted to make the color blue, this is what we would type:
- h1{ color: red;}
- **NOTE: Make sure to add a semicolon after each declaration! This is what separates one declaration from another. If no semicolon is added, your code will not show up in the browser..**

3. Where can we add CSS?

-So, how are we able to get some rockin’ CSS in our code? You’ll be happy to know there are 3 ways to do it!

1. **External CSS**
-You can create another cold in your IDE with a ‘.css’ ending. Make sure you add a relative link that refers back to the CSS file and voila! You are now able to use your CSS file to add changes to your HTML code!! This oftentimes is the best option for writing CSS for your HTML file without having two coding languages on the same file--Yikes!.

2. **Internal CSS**

- Another option is adding the 'style' tag(s) in the ‘head’ tag in your HTML document. This lets you make changes to your CSS on the same file as your HTML.

3. **Inline CSS**
-The last option is a little quicker if you’re feeling kinda lazy. The ’style’ value is put directly after the HTML element value. Your CSS combines with your HTML to create the same effect as Internal and External CSS.

Happy Coding!

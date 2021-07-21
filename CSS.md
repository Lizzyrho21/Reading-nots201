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

 # CSS Boxes

All content in CSS can be placed inside invisible boxes when first created. If we want to customize these boxes, we have to understand whats on the inside and outside.

A. Border, Padding, and Margin

1. Border

The border seperates the edge of one box from another. It can either be visible or invisible (0px wide). It also seperates the content from the margin.

- We can style the border color, size, or format using different properties.
1. border-color
2. border-style

2.  Margin
Margin sits outside of the box itself. it is basically just white space in a page.
We can set the size for margin with px, ems, or percentages!

h1{
    margin: 20px 30px 20px 30px;
}

The example above would set the top and bottom margin to 20px, and the left and right margins to 30px!

3. Padding
Padding seperates itself from the content and the border. it's just the space around the content. 
We can set the size for padding with px, ems, or percentages!

EX. 
h2 {
    padding: 30px;
}

The example above would set all sides of the padding equal to 30px!



B. Box dimensions 

1. Width 
We can use width to obviosuly size the width of our content. 
We can use percentages, ems, or just px (pixels). Pixels are widely used by many developers. 
- We have a min-width property that, when set, sets the content to only stay within the assigned width when the screen reaches equal to or beyond the smallest size.

- We use a max-width property that when set, sets the content to only stay within the assigned width when the screen reaches equal to or beyond the largest size.

Happy Coding!!

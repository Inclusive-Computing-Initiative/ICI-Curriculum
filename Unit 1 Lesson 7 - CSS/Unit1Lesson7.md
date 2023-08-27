# CS47

## CSS

Using HTML can help us create a great framework, or a skeleton, but a skeleton isn't very pretty so we use CSS. CSS is like the skin of the skeleton and it adds details, colors, and styles to the HTML.

### What is CSS and how do we use it?

CSS, or Cascading Style Sheets, is how we style or decorate our HTML code. Without it, HTML looks bland and boring with the same fonts, colors, and alignment.

First of all, CSS and HTML are different languages. Different languages have different functions and syntax, which is like grammer. For example, English and Spanish have different grammer and words, just like HTML and CSS.

To create a CSS file, create a new file and name it Style.css. We now write our CSS code.

### Code

Let's look at a &lt;h1> tag that says Hello on the body of a HTML page without any CSS. It's a bit boring isn't it.

<pre>
    <img src="website-bland.png">
</pre>

Let's fix it. First let's add a background color to the &lt;body> tag of our html page.

    body {background: #009c9a}

Here we tell the CSS program we want the Body tag to have a specific blue color using a hexadecimal value, which is a code we use to get specific colors.

Next we should make the &lt;h1> tag go to the center and change it's color.

    h1 {
        text-align: center; 
        color: purple;
        font-family: cursive;
    }

We added color element which makes the text purple. We also added a text-align, which tells the text where to be and since we added it to the center, the next will be in the center. We also added a font-family, which is like adding a font in google docs. It makes our text look less bland.

This is what the improved HTML page looks like
<pre>
    <img src="website-colorful.png">
</pre>

#### Syntax

For CSS to work we have to add the tag of the element we're trying to improve, for example we use body for the &lt;body> tag. Then we add a pair curly brackets ( {} ) and add our styles inside them.

Also in the end of every style we add a semicolon ( ; ) to tell the computer that we're done with that style and were moving on to the next one. 

We change the syntax when we use classes, which you'll learn next lesson, by adding a . and then the class name.

For example we can do:

    .home {
        background: "red"
    }
This adds red to all the elements with the class home, but as I said Class is something we'll learn next time so don't worry about it too much.

---
Congrats! Now you know the basics of CSS and can make HTML pages look way cooler. Now you should try to make a CSS page and give it a background color and make the text a different color. Good Luck!
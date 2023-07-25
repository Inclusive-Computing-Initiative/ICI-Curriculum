# CS43

## Text

Many websites use text in order to display its contents.
In fact, what you are reading right now is text displayed on a website!
Cool right? Now how did we do it?

### Paragraph Element

Well, we used the &lt;p> tag, also known as the "paragraph tag", to display our text.
Let's look at an example:
    
    <body>
        <p>Hello, World!</p>
    </body>

In this example, the text that we want to display is "Hello, World!" In order to display it, we put the &lt;p> tag in the front and back of the text.
Try to think of displaying text as a book. The &lt;p> tags represent the front and back cover while the content inside is represented by the pages because that's what the reader sees.
Believe it or not, there is another way to display text, and this is to simply type it into the file like this:
    
    <body>
        Hello World!
    </body>

Why would we want to do extra work by surrounding the content with the &lt;p> tag when we could just type it in?
Let me show you.
This is HTML using &lt;p> tags:

    <body>
        <p>The paragraph tag creates a new line or "paragraph" whenever we use it.</p>
        <p>This allows for a more organized website.</p>
    </body>

The example above outputs:

    The paragraph tag creates a new line or "paragraph" whenever we use it.
    This allows for a more organized website.

This is HTML without using &lt;p> tags:

    <body>
        The paragraph tag creates a new line or "paragraph" whenever we use it.
        Not using them makes the HTML and website harder to read.
    </body>

The example above outputs:

    The paragraph tag creates a new line or "paragraph" whenever we use it. Not using them makes the HTML and website harder to read.

As you can see, the &lt;p> tags make the website and HTML easier to read and edit when needed.

### Headings Element

As you can see, the <p> tags make the website and HTML easier to read and edit when needed.
Another way of organizing a website or document is by using headings.
In HTML, we use the &lt;h1>, &lt;h2>, &lt;h3>, &lt;h4>, &lt;h5>, and &lt;h6> tags to insert a heading.
Now why might we need 6 tags just to insert a heading?
The answer is to further organize a website or document.
Some sections might have sub-sections that describe the first section.
Let's take a look at an example:

    <body>
        <h1>HTML</h1>
        <p>Hyper Text Markup Language</p>
        <h2>The Paragraph Tag</h2>
        <p>Puts text in paragraph format.</p>
        <h2>The Heading Tag</h2>
        <p>Separates ideas and sections in a document or website.</p>
    </body>

As you can see, the main idea is inside the &lt;h1> tag while the &lt;h2> tag described an idea that supports the idea inside the &lt;h1> tags.
Notice how there is also a difference in size between the h1 and h2 tags. This size decreases from h1 to h6 (h1 being the largest and h6 being the smallest).

### Styles

Currently our text is very plain. Whenever we use the &lt;p> tags for text, the text is black, and the size and font are the same.
Let's see how we can change the text styles:

    <body>
        <p style="color:red;">This text is red!</p>
        <p style="font-size:16pt;">This text is 16pt font!</p>
        <p style="font-family:verdana;">This text is Verdana font!</p>
        <p style="color:red; font-size:16pt; font-family:verdana;>This text is red, 16pt, and Verdana font!</p>
    </body>

This is the output for the HTML above:

<pre>
<p style="color:red;">This text is red!</p>
<p style="font-size:16pt;">This text is 16pt font!</p>
<p style="font-family:verdana;">This text is Verdana font!</p>
<p style="color:red; font-size:16pt; font-family:verdana;">This text is red, 16pt, and Verdana font!</p>
</pre>

As you can see, we used the "style" attribute in order to change the style of the content in the &lt;p> tags.
Inside the "style" attribute, we have the property (what we want to change) and value (what to change it to).
The structure of the "style" attribute follows:

    <p style="property:value;">Hello, World!</p>

Going back to the book example, think of attributes to a tag as how books are different from each other. Some books might have small text and big pages while others have big text and big pages.
Now that you know how to use text in HTML and how to style text, it's your turn!

# CS48

## HTML Class Attribute

Isn't it annoying whenever we try to style some text and have to add code to every single tag?
What if we could just style a group of text all at once?
That would be very convenient wouldn't it?
Well with the "class" attribute, this becomes a reality.

### The Class Attribute

The "class" attribute allows us to group many pieces of code together.
Let's take a look:

```html
    <div>
		<p>Styling text over and over again is so annoying.</p>
		<p>I know, right? It's so tedious.</p>
		<p>I wish there was a way to style text quickly.</p>
    </div>
```

Here, we have a couple paragraph tags all contained within a div.
Let's group the paragraph tags together using a class while also giving the class a name of "dialog":

```html
    <div>
		<p class="dialog">Wow, that's so cool!</p>
		<p class="dialog">I am now part of the "dialog class.</p>
		<p class="dialog">Me too!</p>
    </div>
```

We have now successful put the three paragraph tags under the dialog class.
Still though, declaring a class every time we make a paragraph tag can get very repetitive right?
Is there a way for us to give this block of text the "dialog" class more efficiently?
The answer is yes.
We can give the div the class of "dialog", and now when we change the "dialog" class, all the text inside will be changed:

```html
    <div class="dialog">
		<p>We're still part of the "dialog" class.</p>
		<p>But my paragraph tag doesn't have the class attribute, are you sure?</p>
		<p>I checked, and we are still part of the "dialog" class.</p>
    </div>
```

### Integrating CSS

Now all of the changes we have made just now won't be seen unless we do something with it.
Let's use some of that CSS we learned last lesson to make the text look cool:

```CSS
    .dialog {
        background-color: #000000;
	    color: #4AF626;
	    font-size: 20px;
	    border-style: solid;
	    border-color: #4AF626;
    }
```

Using the "dialog" class as well as the CSS, we can make this with minimal effort:

```html
<style>
	.dialog {
		background-color: #000000;
		color: #4AF626;
		font-size: 20px;
		border-style: solid;
		border-color: #4AF626;
	}
</style>
	
<div class="dialog">
    <p>Wow! I look so cool right now.</p>
    <p>I feel like I came right from the terminal.</p>
    <p>That's pretty ironic.</p>
</div>
```

Super cool and convenient right?
But what happens if there are multiple classes within each other?
What will happen?
Let's first take a look at how classes can clash with each other:

```html
    <div class="dialog">
      	<p class="Steven">I have a name now!</p>
	   	<p>When do we get ours?</p>
	   	<p>Yea! That's not fair!</p>
    </div>
```

Super cool and convenient right?

### Working With Multiple Classes

What happens if there are multiple classes within each other?
Let's first take a look at how classes can clash with each other:

```html
    <div class="dialog">
      	<p class="Steven">I have a name now!</p>
	   	<p>When do we get ours?</p>
	   	<p>Yea! That's not fair!</p>
    </div>
```

Looking at the HTML above, is the first paragraph tag in class "Steven" or in class "dialog"?
Well the answer is that it belongs to both classes.
In fact, a tag can have as many different tags as we want it to have.
Let's take a look at how we do that:

```html
    <div class"dialog">
       <p class="Steven Sophomore HighSchool">Wait, you two are older than me?</p>
	   <p class="Jessica Senior HighSchool">Yeah. In fact, we are two years older than you.</p>
	   <p class="Carson Junior HighSchool">You still have a long way to go, Steven.</p>
    </div>
```

Can you name the classes that each person is in?
The answer is below:
Steven is in classes Steven, Sophomore, HighSchool, and dialog.
Jessica is in classes Jessica, Senior, HighSchool, and dialog.
Carson is in classes Carson, Junior, HighSchool, and dialog.
If that's the answer you got, congratulations!
If that's not the answer you got and you have questions, be sure to let a mentor know, but congratulations on giving it a shot!

### Styling Multiple Classes and Tags

Now we've talked about multiple tags having the same class, but what if I want to group different types of tags together?
Is that allowed?
Yes! We can.
Let's take a look at how we can do this and how it can be helpful:

```html
    <style>
		.dialog {
			background-color: #000000;
		}
		.Senior {
			color: #4AF626;
		}
		.Junior {
			color: #9A1BE4;
		}
		p.HighSchool {
			color: #E7D718;
		}
		h2.HighSchool {
			color: #E1841E;
     	}
		HighSchool {
			text-align: left;
		}
    </style>

    <div class"dialog">
	  	<h2 class="HighSchool">Conversation Between High Schoolers</h2>
      	<p class="Steven Sophomore HighSchool">The class attribute is super useful, right?</p>
	   	<p class="Jessica Senior HighSchool">Yeah! I've been using it whenever I write with HTML.</p>
	   	<p class="Carson Junior HighSchool">I completely agree. The class attribute has saved me so much time.</p>
    </div>
```

Let's analyze the code above starting with our div.
Most of the elements in the div are the same, but now we have a h2 tag with a class of "HighSchool".
Between the style tags, we have a bit of CSS.
You may have noticed that we have 3 selectors containing the class "HighSchool".
Before you read on, take a guess!

The 3 different selectors containing the class "HighSchool" specifies which tags to apply the style to if the tag also has a class of "HighSchool".
For example, the p.HighSchool selector specifies styles for the paragraph tags that have the class "HighSchool".

---

Congratulations!
You have now learned about classes.
Try and integrate classes into your own HTML and see how it helps!

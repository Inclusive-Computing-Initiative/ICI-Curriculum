# CS44

## The &lt;a> Tag
In HTML, you use the &lt;a> tag, or the anchor element, to create hyperlinks. Hyperlinks are like special links that connect one webpage to another on the internet. They work with an attribute called "href" to make it happen. When you click on a hyperlink, it takes you to a different webpage, just like how the doors in your house take you to a new room. With hyperlinks, you can make doors that lead you to a new place on the internet! It's like a magical doorway that helps you explore and discover exciting things online. It doesn’t just link other websites, it can attach pictures, emails, phone numbers, and more to your website.

Let’s see this in action!

## Linking to Another Website
I want to flair up my website with my favorite youtube video! I’ll need to make a hyperlink to make a door on my website that brings me to that video. I have to tell the computer to go to that video with the &lt;a> tag. 

&lt;a href=”https://www.youtube.com/watch?v=B03NzkiNORw”>Youtube Video!&lt;/a>

But how does this code work? It starts by opening the <a> tag with the “less than” symbol (the crocodile mouth opening to the right). Next, a href=”link”. You have to put your link between two quotation marks or it won’t work. Now, you have to close the first part with the “greater than” symbol (the crocodile mouth opening to the left). Before we close the &lt;a> tag with “&lt;/a>”, put the text you want to see that will take you to the website you chose when you click on it. Now you can finish with “&lt;/a>” to close it.

## Linking an image
Linking an image is very similar to the way we linked a website. However it is three lines of code instead of one. Once again we have to open the <a> tag and add the link inside.

&lt;a href=”https://www.youtube.com/watch?v=B03NzkiNORw”>

Don’t forget the quotation marks!
Before, in the earlier line of code, we put “Youtube Video!” which we would see on your website instead of just a link. Now you are replacing those words with an image instead so when you click that image it sends you to the website you want or in this case the youtube video. To make it an image you will need the &lt;img> tag. Let’s write the second line and see.

&lt;img src=”https://media.tenor.com/qnoSfZYajHAAAAAC/spinning-banana-banana.gif”>

Then you close the &lt;a> tag with one more line.

&lt;/a>

The src is telling the computer the source of the image. I used a banana because I love bananas. Now when you click the banana it will bring you to the youtube video! Another way we could get a picture is to replace the banana.png with an image address you find online. Just find a picture you like, right click it, and then click copy image address and put it between the quotation marks.

All together it should look like this:

&lt;a href=”https://www.youtube.com/watch?v=B03NzkiNORw”>
&lt;img src=”https://media.tenor.com/qnoSfZYajHAAAAAC/spinning-banana-banana.gif”>
&lt;/a>

Congratulations! Now your website can connect to the world wide web!

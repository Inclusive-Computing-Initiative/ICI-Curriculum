# CS44

## Images

A website with only words seems kind of boring doesn't it?
Let's add some images to keep the viewer engaged in our website.
To add an image, we use the &lt;img> tag.
The way we use the &lt;img> tag is a little different from the way we use the &lt;p> or &lt;h1> tags.
Let's take a look:

	<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/Taka_Shiba.jpg/800px-Taka_Shiba.jpg" width="700" height="500" alt="A Very Happy Dog" style="border:10px solid green;">

<pre>
	<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/Taka_Shiba.jpg/800px-Taka_Shiba.jpg" width="700" height="500" alt="A Very Happy Dog" style="border:10px solid green;">
</pre>

Notice how when we are inserting an image using the &lt;img> tag, we don't need to close it with an &lt;/img> tag.
Unlike the text tags (&lt;p>, etc.) that are similar to a book, the &lt;img> tag is more like a poster that has all the information on one page.

### Attributes

What makes the &lt;img> tag, and most other tags, different from one another is its attributes, so let's take a look at some of them.

#### src

The "src" attribute tells the computer where to find the image. In the example above, the src attribute pointed to the image at https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/Taka_Shiba.jpg/800px-Taka_Shiba.jpg.

#### width and height

Next, the "width" and "height" specifies how wide and tall the image is respectively in pixels. The example above specified the width as 700 pixels and the height to be 500 pixels. When changing the size, be weary of accidentally stretching an image and making the image look weird.

#### alt

The "alt" attribute gives the computer alternative text to output just in case the image isn't avaliable for some reason. Maybe the src tag is wrong or the image was deleted. Either way, the alt attribute is a great way to describe the picture to the viewer in case it doesn't show up.

#### style

Just like the text tags, we can also style the image using the "style" attribute. In the example above, the style attribute specified that the image should have a border that is 10 pixels, solid, and green.

---

Now that you know the basics of adding an image to your website, it's your turn!
Find an image that you like online, right-click the image, and press "Copy image address" to get the url for a picture online.

# HTML Basics
---

**Learning objective**: Learn the basic structure of a simple HTML page.


#### Exercise
---

Please create a simple webpage and mark up your own resume template. Use **only** pure **HTML tags** and do not worry to much about the styles itself. You may use the **[example](http://resume.taqquikarim.com/)** above as reference.

If you do not feel comfortable using your own credentials in this exercise, feel free to make up a persona or use a celebrity (ie: **Mickey Mouse**).


---


HTML stands for **Hyper Text Markup Language**. It is a set of annotations that help parsers (ie: search engines) **understand** the nature of the information that is present on the page.

Think of it like an outline that describes the high level importance of different elements of your webpage.

#### Basic setup
---

Your typical HTML file will look like this:

```html
<!doctype html>
<html>
 <head>
 <!--
 the HEAD section of html does not have any content
 that the user can see

 instead, we place things like:
 page title
 external css links
 SEO keywords
 here
 -->
 <meta charset="utf-8">
 <title>My First Awesome Site</title>
 </head>
 <body>
 <!--

 the BODY section will contain all the tags
 that the user can _SEE_ and _INTERACT_ with
 -->
 </body>
</html>
```

#### Key components
---

**`<!doctype html>`**

This tag tells the browser to read our HTML content as HTML5, the latest and greatest revision of the HTML spec. We MUST include it as the first thing on our .html files. I usually type it as all lower case, but it's common practice to also type as: <!DOCTYPE html>

**`<html>`**

This is the root tag. Basically, all other tags in your html file must live inside this tag. Note how on the bottom of the code snippet, we have a "". This is called closing a tag and we must close all tags that we open (with the exception of a few). If we do not do this, our HTML markup becomes invalid.

**`<head>`**

This section contains content that does not show the user things. Typically, we would expect to see things such as the page title, external links, and SEO tags here.

**`<body>`**

All the magic happens here. All the tags the user interacts with should live in this tag.

#### Commonly used HTML Tags
---

```html
<!--
 the h1 - or heading one - will have the most important text on page 
 by the old guard, we should really only have one h1 per page
 -->
 <h1>Hello, Wrold</h1>

 <h2>This is a h2</h2>

 <h3>This is an h3</h3>

 <h4>This is an h4</h4>

 <h5>This is an h5</h5>

 <h6>This is an h6</h6> 

 <!--
 this is an inline element
 unline the block element, which is meant to provide structure
 the inline element is interpreted as content
 this means that will appear next to one another
 -->
 <strong>This is an inline element</strong>
 <strong>This is another inline element</strong>

 <!-- this is a block element so it will NOT be on the same line -->
 <h1>Will this be on the same line?</h1>

 <!-- 

 differences between block elements and inline elements
 block: takes up entire width of page unless otherwise told 
 (we don't know how yet)
 we can impose dimensions on block elements
 inline: meant to be content or text
 we cannot impose dimensions on inline elements 

 -->

 <!-- how to add more spaces or line breaks?? -->
 <h1>THIS will have many &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; spaces</h1>

 <h1>This is <br> Sparta</h1>

 <a href="http://www.google.com">Hello, Wrold I'm a link, yo</a>

 <!--
 this is one mode
 <tagName attribute1="someValue" attribute2="someOtherValue"></tagName>

 this is a self closing tag
 <tagName attribute1="someValue" attribute2="someOtherValue">
 --> 

 <!--
 convention: 
 external links open up in new tab
 absolute URLs

 internal links open up in same tab
 relative URLs
 -->

 <a href="http://www.google.com" target="_blank">Hello, Wrold I'm ALSO a link, yo</a>

 <em>This is an em</em>

 <p>This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.This is a paragraph.</p>

 <img src="http://placekitten.com/g/200/300">
 <span>This is a kitten. S/he is cute.</span>

 <ul>
 <li>This is a list item <div></div></li>
 <li>This is another list item</li>
 <li>This is a third list item</li>
 </ul>

 <ol>
 <li>This is an ordered list item</li>
 <li>This is another ordered list item</li>
 <li>This is a third ordered list item</li>
 </ol>

 <div></div>

 <span></span>
```

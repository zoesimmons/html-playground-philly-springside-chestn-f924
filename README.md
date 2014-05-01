---
  tags: html, css, kids
  languages: html, css
---

# HTML Playground

## Instructions

You know that really popular blogging platform where people post cat gifs? Wouldn't it be cool to see how that works?

In this lab, you'll be filling in your own HTML elements and attributes to modify a Tumblr-like website.

## What is HTML?

HTML is a markdown language that allows you to render whatever you want on a webpage. Think of each element as a holder for what you want on the page, whether it's text, images, gifs (which are actually images, but obviously better), and videos.

Every HTML element is expressed with and start and end tag, with the content you want displayed on your website in-between them. Let's say I wanted a headline on the top of my page. I would use the `<h1>` element and write:

`<h1>My Favorite GIFs</h1>`

### The Format of every HTML webpage...

#### ...looks like this:

```
<html>
<head>
  <title></title>
</head>
<body>

</body>
</html>
```

Everything on your page should be surrounded by `<html></html>` tags. The `<head></head>` tags encapsulate information about the page, like what type of language it is, and which stylesheets and other files we would like to include (more on that later). In-between

## Some helpful HTML elements
<h1></h1> This tag is used for main headers of pages. It denotes a much bigger font.
<h2></h2> This tag is useful to subheaders. Think of this like on a business card, when someone lists their name, and then their job title is listed just a little bit smaller. There are also h3, h4, h5, and h6 tags. The font gets progressively smaller as the numbers get bigger. h1 is much larger than h6
<p></p> Use this tag for chunks of text. The p stands for paragraph
<br> HTML doesn't understand whitespace. Which means if in your HTML document you push return a bunch of times and have a lot of empty lines, your browser won't recognize those empty lines. Use <br> to manually create those white lines. <br> is one of the only tags that doesn't require a closing tag
<a href=""></a> The <a> tag is a link tag. The href portion is considered an attribute of the <a> tag. In the quotes following the `=` is where you would put the website you are trying to link to. For example, if you were trying to link to google, you would write <a href="www.google.com">CLICK HERE TO GO TO GOOGLE</a>
<img src=""></img> The img tag is for images. `src` is considered an attribute of the <img> tag. It's where you would list the image you are trying to display on your website. You can link directly to an image on the website, in which case you would list the URL to the image, or you can link to images on your computer, in which case you would list the path to the image.  




## Note

Don't worry if this don't fully make sense. It's a playground space for you to explore some HTML and render your fave gifs on a page. We're going to go more into detail on what's happening after this lab.

Have fun! :)
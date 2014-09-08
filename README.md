---
  tags: html, kids
  languages: html
  type: lab
  level: 1
---

# HTML Playground

You know that really popular blogging platform where people post cat gifs? Wouldn't it be cool to see how that works?

In this lab, you'll be filling in your own HTML elements and attributes to modify a Tumblr-like website!

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

Everything on your page should be surrounded by `<html></html>` tags. The `<head></head>` tags encapsulate information about the page that won't show up on your page when viewing it, like which stylesheets and other files you would like to include (more on that later). In-between the `<title></title>` tags is the title of your site. You know the text on a tab in your browser? That's the title.

Everything you want displayed on your page, all text, images, and videos, lives within the `<body></body>` tags. That `<h1></h1>` from before would live within the body tags.

## Some helpful HTML elements

`<h1></h1>` This tag is used for main headers of pages. It denotes a much bigger font.

`<h2></h2>` This tag is useful to subheaders. Think of this like on a business card, when someone lists their name, and then their job title is listed just a little bit smaller. There are also h3, h4, h5, and h6 tags. The font gets progressively smaller as the numbers get bigger. h1 is much larger than h6

`<h3></h3>` Even smaller header. Think of this when you're using titles for blog posts, etc.

`<p></p>` Use this tag for chunks of text. The p stands for paragraph

`<br>` HTML doesn't understand whitespace. Which means if in your HTML document you push return a bunch of times and have a lot of empty lines, your browser won't recognize those empty lines. Use `<br>` to manually create those white lines. `<br>` is one of the only tags that doesn't require a closing tag

`<a href=""></a>` The `<a>` tag is a link tag. The href portion is considered an attribute of the `<a>` tag. In the quotes following the `=` is where you would put the website you are trying to link to. For example, if you were trying to link to google, you would write `<a href="www.google.com">CLICK HERE TO GO TO GOOGLE</a>`

`<img src="">` The img tag is for images. `src` is considered an attribute of the `<img>` tag. It's where you would list the image you are trying to display on your website. You can link directly to an image on the website, in which case you would list the URL to the image, or you can link to images on your computer, in which case you would list the path to the image.

`<title></title>` Used for the title of your site. This is what will be displayed in the browser tab.


## Challenge:

Open up `index.html` in Sublime Text and check out what's going on. Look for the tags we've learned about from above and try to figure out what they're doing.

It's helpful to have `index.html` open in your browser at the same time. Make some changes to the file and see what happens the in browser by refreshing the page! Remember you won't see the changes in the browser if you haven't saved your changes in your HTML file.

Look for comments (any text that's between `<!--  -->` tags won't show up on the page) for some helpful hints on where to include different things.

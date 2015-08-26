# HTML Playground

<img src="https://after-school-assets.s3.amazonaws.com/cat.gif" width="200px" align="right" hspace="10"> 

You know [Tumblr](http://www.tumblr.com), that really popular blogging platform where people post tons of cat gifs? Wouldn't it be cool to see how that works? In this lab, you'll be filling in your own HTML elements and attributes to modify a Tumblr-like website!

## The format of every HTML site looks like this:

```html
<html>
<head>
  <title></title>
</head>
<body>

</body>
</html>
```

All the code in `index.html` should be surrounded by `<html></html>` tags, just like in the code example above. This tells our browser we're writing HTML.

The `<head></head>` tags encapsulate information about the page that won't show up on your page when viewing it, like which stylesheets and other files you would like to include (more on that later). 

In-between the `<title></title>` tags is the title of your site. You know the text on a tab in your browser? That's the title.
The title tag in your `index.html` should look something like this:

<img src="https://s3.amazonaws.com/after-school-assets/title-tag.png">.

After you save your changes, and look at it in the browser, you'll see the text in the tab of the browser like this:

<img src="https://s3.amazonaws.com/after-school-assets/title-tag-in-browser.png">

Everything you want displayed on your page, all text, images, and videos, lives within the `<body></body>` tags. 

That `<h1></h1>` from before would live between the opening and closing the body tags.

When you open this site in the browser, you'll notice the page is fully styled for you. That code to style the page has been written for you in `style.css`. This stylesheet dictates where and in what style the HTML should be displayed. Don't worry about the code in `style.css` quite yet. We'll get to that soon!

## Some helpful HTML elements

`<h1></h1>` This tag is used for main headers of pages. It denotes a much bigger font.

`<h2></h2>` This tag is useful to subheaders. Think of this like on a business card, when someone lists their name, and then their job title is listed just a little bit smaller. There are also h3, h4, h5, and h6 tags. The font gets progressively smaller as the numbers get bigger. h1 is much larger than h6

`<h3></h3>` Even smaller header. Think of this when you're using titles for blog posts, etc.

`<p></p>` Use this tag for chunks of text. The p stands for paragraph

`<br>` HTML doesn't understand whitespace. Which means if in your HTML document you push return a bunch of times and have a lot of empty lines, your browser won't recognize those empty lines. Use `<br>` to manually create those white lines. `<br>` is one of the only tags that doesn't require a closing tag


### Challenge:

The point of this lab is to be exactly what it's called: A playground! What that means is that this is a place for you to experiment with HTML. Don't worry about making mistakes. We want you to get comfortable making mistakes, being okay making mistakes, and then learning from them.

Take a look at the [Mozilla Developer Network HTML tag documentationn](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) for suggestions of tags to play with. Have fun making this site yours, and mess around with different HTML tags.

### Get Started: 
Click the `Open In Nitrous` button at the top of Learn. This will bring you to Nitrous. In the left-hand side in the navigation bar, you'll want to look in the `code` directory, and look for the `HTML-playground` directory. Double click on `index.html` inside the `HTML-playground` directory to open it in the text editor. Look for comments (any text that's between `<!--  -->` is a comment, and it won't show up on the page) for hints. Look for the tags we've learned about from above and try to figure out what they're doing.

It's helpful to have `index.html` open in your browser at the same time. You can do that by entering in terminal: 

```
python -m SimpleHTTPServer 3000
```

Once you have the server running, select `preview` and then `port 3000`.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-preview.png" alt="nitrous preview">

Make some changes to the file, save those changes and see what happens the in browser by refreshing the page! Remember you won't see the changes in the browser if you haven't saved your changes in your HTML file.

Make sure to stop your server when you're done testing by hitting `control` + `c`.

### When You're Finished:

In order to mark this lab as finished, in this Nitrous terminal, in the directory for this lab (`nitrous < code < labs < html-playground`), enter `learn submit`. This will push your work up to GitHub, and mark this lab as complete!

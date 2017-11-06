# IceBreakers Site Navigation HTML Lab

## Objectives

1. Turn plain text into a link by wrapping it in `<a>` tags.
2. Create a fully-functional navigation header that links to the site's main pages.

## Instructions

Open `index.html` in your text editor. You'll see the code that we wrote in a previous lab. In this lab, you're tasked with extending the plain text navigation header by adding hyperlinks to other pages.

To pass the tests for this lab, you need to wrap three different pieces of text in `<a>` tags, turning them into links:
  - `New Questions`
  - `About`
  - The `Icebreakers` inside the `h3` element

You can run the tests with this lab via `learn`. Make sure you save the file before running the test suite. Failing tests will provide helpful error messages that you can use to debug your code — read them closely for hints!

This is the entire description of the navigation structure:

```
Icebreakers Site Navigation
  begins with a valid doctype
  has a top-level <html> tag to enclose the document
  within <html>
    contains a <head> tag to enclose the header
    within <head>
      contains a <title> tag to enclose the site title
  within <html>
    contains a <body> tag to enclose the body of the document
    within <body>
      contains a <header> tag to enclose the site header
      within <header>
        contains a <nav> tag to enclose the site navigation 
        within <nav>
          contains a <ul> tag to enclose the site navigation 
          within <ul>
            contains a pair of <li> tags for linking to other pages 
            within the <li> tags
              each contains an <a> tag to link to another page 
      within <header>
        contains an <h3> tag to enclose the site's title 
        within <h3>
          contains an <a> tag to link back to the site's homepage 
  w3c validation
    is a valid w3c document
```

## Viewing your work in the browser

While working through these assignments, your general workflow should center on writing code in the text editor and periodically running the test suite in the terminal to check your work.

Another great way to track your progress is to open up the HTML document in your browser and watch how each change you make in the text editor affects the visual layout in the browser. If you're using a local development environment, you can open the HTML file directly in your browser. If you're coding in the Learn IDE, check out this [Help Center article](http://help.learn.co/the-learn-ide/common-ide-questions/viewing-html-pages-in-the-learn-ide) that explains how to spin up and connect to a simple remote server.

Once you have the HTML document open in your browser, you can make changes to it in the text editor, save the file, refresh the page in the browser, and see the changes instantly.

## Resources

* [W3S — HTML `<a>` Tag](https://www.w3schools.com/tags/tag_a.asp)

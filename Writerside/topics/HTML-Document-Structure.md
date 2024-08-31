# HTML Document Structure

All HTML documents have the primary format shown below:

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    <p>Hello, World</p>
</body>
</html>
```

Let's discuss this structure.

## ```<!DOCTYPE html>``` declaration
The first line we see is the ```<!DOCTYPE html>``` declaration, this line declares the document type and version of HTML being used and is usually placed at the very beginning of the document.  
The line specifically tells the browser that the document is an HTML5 document, which is the current standard for HTML, this ensures that the web page is rendered correctly in the browser.

## ```<html></html>``` tag
The ```<html>``` tag is the root element that wraps all other html elements.  
It comes directly after the ```<!DOCTYPE html>``` declaration.  
It takes/nests only two tags (more about nesting HTML elements later):
- The ```<head></head>``` tag.
- The ```<body></body>``` tag.

## ```<head></head>``` tag
This tag wraps metadata and links to external resources such as stylesheets and scripts.  
It comes immediately after the opening ```<html>``` tag (this is very important).  
Some of the tags that you will often see come in this section include but not limited to:
- **```<meta>``` tag**: provides metadata such as character encoding, viewport settings, and descriptions.
- **```<title></title>``` tag**: specifies the title of the webpage, which appears in the browser tab.
- **```<link> tag```**: links to external resources like CSS files, font files et.c.
- **```<script></script> tag```**: links to external JavaScript files or contains inline scripts.
- **```<style></style>``` tag**: contains internal CSS style declarations.

## ```<body></body>``` tag
This tag contains the actual content of the webpage that will be visible to the users/visitors of our page.  
It comes directly after the ```<head></head>``` tag.  
This is where we place all the visible content of the web page, ie text, images, links and other multimedia content that users can interact with.
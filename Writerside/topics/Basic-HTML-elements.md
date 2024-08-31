# Basic HTML elements

_[follow along](Your-First-Simple-Webpage.md) in your code editor_

## Headings
In HTML, headings are defined with the ```<h1>``` to ```<h6>``` tags:

```HTML
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```
![headings](headings.png)

NOTE: The difference between h1 to h6 is not the size, the difference is the importance with h1 being the most important to h6 being the least important heading.  
Imagine your web page is like a book, and the headings (```<h1> to <h6>```) are like the table of contents that organize the content into sections and subsections, helping readers (and search engines) navigate the information.  
- h1 would be the main title of the book, just like a book's title on the cover.
- h2 would be major chapters heading, providing the first level organization within the main topic.
- h3 would be sections headings within chapters
- h4 would be subsections headings within the sections
- et.c

## Paragraphs
In HTML, paragraphs are defined with the ```<p></p>``` tag:
```HTML
<p>This is a paragraph</p>
<p>What is HTML?</p>
<p>
    HTML, or HyperText Markup Language, is the standard language used to
    create and design web pages. It defines the structure and layout 
    of a web page by using a variety of elements and tags.
</p>
```
![Paragraph](paragraph.png)

## Links
HTML links are defined with the ```<a></a>``` tag.  
A link is a reference in an HTML document that allows visitors to navigate from one webpage to another or to different sections within the same page.  
Within the ```<a>``` tag, we pass the ```href``` attribute (more about attributes later) which specifies the destination of the link as shown below.

```HTML
<a href="https://www.google.com/">Visit google</a>
<a href="https://www.facebook.com">Open facebook</a>
```
![links](links.png)

When these links are clicked, they will open their respective pages within the same browser tab.  
Sometimes we don't want this since it might make visitors of our page navigate away from our page.  
What we want instead is for the pages to open on a new tab and let our page stay on the current tag.  
This is why we add an attribute called ```target``` and set its value to ```_blank```:
```HTML
<a href="https://www.google.com/" target="_blank">Visit google</a>
<a href="https://www.facebook.com" target="_blank">Open facebook</a>
```

## Images
We can also add images to our HTML document, we do so using the ```<img />``` tag.  
The img tag is a self-closing tag.  
It takes two important attributes:
- ```src```: specifies the path to the image file.
- ```alt```: specifies a value to be used by screen readers to describe the image for example to visually impaired people, also, if the image can't be loaded correctly by the browser, the text in alt attribute will be shown in the place of the image.

First, find your favorite image and place it in the same level as your HTML document ie

![place the image in the same level as your html document](image_placing.png)

now use the img tag and provide the path to this image:

```HTML
<img src="kid.jpg" alt="a happy kid jumping on a bright sunny day">
```
![img tag output](img-output.png)

Assuming the image can't be loaded by the browser correctly, then the text inside the ```alt``` attribute will be displayed in the place of the image as shown:

![image failed to load](image_failed_to_load.png)

For organisation, we want all our images in one folder:
- Create a folder and call it ```images```.
- Move your image to this folder.
- Your file structure should now look as shown:
![file structure](file_structure.png)

In this case, the path to the image will now be as shown:
```HTML
<img src="./images/kid.jpg" alt="a happy kid jumping on a bright sunny day">
```

We can also add the ```width``` and ```height``` attribute to specify the width and the height of the image in pixels:

```HTML
<img src="./images/kid.jpg" width="240px" height="240px" 
     alt="a happy kid jumping on a bright sunny day">
```
TIP: to make your work easier, specify the width only and let the browser figure out the suitable height for you.

## Comments
An HTML comment is a piece of code within the document (inside the body tag) that is not displayed in the browser when the page is viewed.  
We can use comments to leave notes, explanations and other annotations that can be useful to other developers or anyone looking at our code.  
Comments are ignored by the browser, and they do not affect the visual presentation of the web page.  
To write a comment, open using the ```<!--``` and then write your comment and close using ```-->```

```HTML
<!-- This page is about importance of trees -->
<h1>Importance of trees</h1>
<p>Produce oxygen</p>
<p>Improve air quality</p>
<!-- <h2>How trees produce oxygen</h2> -->
<p>habitat for wildlife</p>

<!-- TODO: Explain how trees support biodiversity -->
```
![comments are ignored](comments_output.png)

As we can see, the comments have been ignored by the browser, this is powerful since we can use comments to leave notes for ourselves as shown above, comment code whose output we don't want displayed et.c.
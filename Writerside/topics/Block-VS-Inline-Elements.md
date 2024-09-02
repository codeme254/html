# Block VS Inline Elements

All elements in HTML are categorized into two main types:
- Block-level elements.
- Inline-level elements.

## Block-level elements
- Block-level elements start on a new line and browsers usually add some space (margin) before and after the element.  
- They always stretch to take up the full width available (of the parent).

```HTML
<h1>An interesting story</h1>
<h2>Chapter 1</h2>
<p>First paragraph: Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus, aspernatur?</p>
<p>Second paragraph: Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit!</p>
<p>Third paragraph: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore, labore?</p>
```
![block elements](block.png)

In the example above, the h1 takes all the available width, same case to the h2 and the paragraphs, the amount of text/content
enclosed by the tags doesn't matter, it will always occupy the full width.  
Examples of block-level elements are: h1-h6 tags, paragraph, ordered and unordered lists et.c

## Inline-level elements
Inline elements do not start on a new line.  
They only take up as much width as necessary.  
```HTML
<a href="https://www.facebook.com">Facebook</a>
<a href="https://www.google.com">Google</a>
<a href="https://www.netflix.com">Netflix</a>
<img src="./images/kid.jpg" alt="a kid jumping while smiling" width="240px">
```
![inline-level elements](inline_elements.png)

In the example above, the links and the image occupy only as much space as they need, and they do not start on a new line.
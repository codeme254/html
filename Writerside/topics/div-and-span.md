# div and span

Both ```<div></div>``` and ```<span></span>``` are primarily used for structuring HTML and applying CSS or JavaScript to specific sections of a webpage.  
The implications of div and span won't be obvious in the webpage. The effect of using these elements becomes apparent only when styles or behaviors are applied to them.  
These tags can also be used to group elements together for styling.  

## The ```<div></div>``` tag
It is a block-level container, meaning it takes up the full width available and starts on a new line.  
Used to group larger sections of content, like multiple paragraphs, images and other block-level elements.  
When used, it doesn't add any visual change to the page by itself, if you don't apply any styles, the presence of the div element will not be noticed.

```HTML
<div>
    <img src="./images/kid.jpg" alt="a kid jumping" width="240px">
    <h2>title of my grouped content</h2>
    <p>Paragraph of my grouped content</p>
    <a href="www.example.com">More information</a>
</div>

<div>
    <img src="./images/kid.jpg" alt="a kid jumping" width="240px">
    <h2>another grouped content</h2>
    <p>another paragraph of another grouped content</p>
    <a href="www.example.com">More information</a>
</div>
```

![grouped content with div](div.png)

## The ```<span></span>``` tag
It is an inline-level container, meaning it doesn't occupy the full width available and does not start on a new line.  
It's often used to style parts of text within a paragraph or to group small pieces of content.  
Similar to div, when used on its own, it won't produce any visible difference on the page.

```HTML
<p>This is a <span>word</span> in a sentence.</p>
```
![span](span.png)
# Nesting HTML elements

There's nothing special about nesting HTML elements, it's all about placing one HTML element inside another.  
This practice is fundamental to building the structure of a web page as it allows for the creation of complex layouts and the organization of content in a hierarchical manner.  
When an element is placed inside another element, the containing element is referred to as the ```parent element``` and the contained element is referred to as the ```child element```.

Here are some examples of nesting:

```HTML
<h1>A heading element</h1>

<a href="https://www.facebook.com">
    <h1>a heading element inside an anchor tag</h1>
</a>
```
In this example, the second h1 element is nested inside an anchor tag, the results will be as shown:

![nesting html elements](nesting_1.png)

Let's place an image inside an anchor tag to render an image link:

```HTML
<a href="https://pixabay.com">
    <img src="images/kid.jpg" alt="a kid jumping while smiling" width="240px">
</a>
```
![image link](img-output.png)

The effect is not visible but the image now acts a clickable link.

This is just a tip of the iceberg when it comes to nesting, nesting is something that you will be doing almost everytime you write HTML.
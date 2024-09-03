# HTML Attributes

HTML attributes provide additional information about HTML elements.  
They are always included in the opening tag of an element and come in name/value pairs, like name="value".  

For example, the img tag takes at least 2 attributes, the src attribute for defining the path to the image
and the alt attribute for providing alternative text for the image.

```HTML
<img src="./images/kid.jpg" alt="a kid jumping while smiling" />
```

Some other popular attributes are:
- **class**: Used to apply CSS styles to elements or to group elements for JavaScript manipulation.
```HTML
<h1 class="title">my title</h1>
```

- **id**: Provides a unique identifier for an element. It is often used to target elements with CSS or JavaScript.
```HTML
<h1 id="intro">Intro title</h1>
```

- **style**: allows inline CSS styling directly on an element.
```HTML
<h1 style="color:blue;">Title</h1>
```

- **href**: Used in anchor tags and specifies the URL of the page the link goes to.
```HTML
<a href="https://www.example.com">Visit Example</a>
```

- **title**: adds a tooltip to the element. When the user hovers over the element, the tooltip appears.
```HTML
<a href="#" title="Go to top">Top</a>
```

There are hundreds of HTML tags each with its own unique functionality.
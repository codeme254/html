# Lists
HTML lists are used to group related items together, presenting them in a structured format.  
HTML lists are essential for organizing content such as menus, navigation links or any other grouped data.  
There are three types of lists in HTML:
- Ordered lists
- Unordered lists
- Descriptive lists

## Ordered lists
Ordered lists are used to display a list of items where the order is important.  
The items will appear number or lettered.  
Ordered lists are defined using the ```<ol></ol>``` tag and then inside the tags we nest ```<li></li>``` tags each representing an item in the list.

```HTML
<p>Here is a list of my favorite fruits:</p>
<ol>
    <li>Apples</li>
    <li>Oranges</li>
    <li>Bananas</li>
    <li>Pineapple</li>
</ol>
```

![Ordered lists](ordered_lists.png)

## Unordered lists
Unordered lists are used to display a list of items where order doesn't matter.  
The items will appear bulleted.  
They are defined using ```<ul></ul>``` tag and then inside the tags we nest ```<li></li>``` tags each representing an item in the list.

```HTML
<p>Here is a list of my favorite fruits:</p>
<ul>
    <li>Apples</li>
    <li>Oranges</li>
    <li>Bananas</li>
    <li>Pineapple</li>
</ul>
```

![unordered lists](unordered_lists.png)

## Description lists
Description lists are used to display a list of terms with their corresponding descriptions.  
The terms are usually presented on the left, with descriptions indented underneath.  
Description lists are defined using the ```<dl></dl>``` tags, inside the tags, we nest ```<dt></dt>``` tags for the term and ```<dd></dd>``` tags for the description as shown.  

```HTML
<dl>
    <dt>HTML</dt>
    <dd>The language that defines the structure of our webpages</dd>
    <dt>CSS</dt>
    <dd>The language that styles our webpages</dd>
    <dt>JavaScript</dt>
    <dd>The language that adds functionality to our webpages</dd>
</dl>
```

![description lists](description_lists.png)

## Nesting lists
Lists can be nested as shown:

```HTML
<ol>
    <li>Technology</li>
    <ul>
        <li>Laptop</li>
        <li>Monitor</li>
        <li>Mouse</li>
    </ul>

    <li>Health</li>
    <ul>
        <li>Gym</li>
        <li>Workout</li>
        <li>Fruits</li>
    </ul>

    <li>Programming</li>
    <dl>
        <dt>HTML</dt>
        <dd>The language for defining structure of webpages</dd>
        <dt>CSS</dt>
        <dd>The language for styling webpages</dd>
    </dl>

    <li>Entertainment</li>
    <dl>
        <dt>Netflix</dt>
        <dd>Movies streaming site</dd>
        <dt>Spotify</dt>
        <dd>Music streaming site</dd>
    </dl>
</ol>
```

![nesting lists](nesting_lists.png)
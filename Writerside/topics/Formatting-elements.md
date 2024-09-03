# HTML Formatting elements
HTML formatting elements are used to define the appearance and meaning of text within a webpage.  
These elements help to emphasize, mark, and structure text, making it more readable and semantically meaningful.  
Let's take a look at all of these elements one by one:  

## ```<b></b>``` for bold text
The tag renders the enclosed text in bold font weight.  
Typically used for stylistic purposes where text needs to stand out visually, but not necessarily with any emphasis or importance.  
```HTML
<p>This is <b>bold text</b>.</p>
<p>
    The student is to <b>adhere to rules and regulations</b> failure
    to which <b>the student will be suspended</b> from school.
</p>
```
![bold text](bold_text.png)

## ```<strong></strong>``` for important text
This indicates that the enclosed text is of strong importance, which will typically be rendered as bold by browsers.  
Used for text that has strong importance or seriousness, where the emphasis is both visual and semantic.  
```HTML
<p>This is <strong>important text</strong>.</p>
<p>
    The student is to <strong>adhere to rules and regulations</strong> failure
    to which <strong>the student will be suspended</strong> from school.
</p>
```
![strong text](strong.png)

## ```<i></i>``` for italic text
This tag renders the enclosed text in italic font style.  
Often used for stylistic purposes, such as to indicate a different tone or to highlight foreign words, book titles, or names. 
```HTML
<p>This is <i>italic text</i></p>
<p>The book <i>The song of ice and fire</i> is one of the best novels</p>
```
![italic text](italic_text.png)

## ```<em></em>``` for emphasized
This tag renders text that should be emphasized, typically rendered as italic by browsers.  
Used for text that requires emphasis, indicating stress or importance in the context, both visually and semantically.
```HTML
<p>This is <em>italic text</em></p>
<p>The book <em>The song of ice and fire</em> is one of the best novels</p>
```
![emphasized text](emphasized_text.png)

## ```<mark></mark>``` for marked text
Highlights text by rendering it with a background color, usually yellow.  
Used to mark or highlight text that is relevant or important in a particular context, like search results.  
```HTML
<p>This is <mark>highlighted</mark> text.</p>

<p>You searched <mark>HTML</mark> here are some results:</p>

<p><mark>HTML</mark> for beginners.</p>
<p>How to learn <mark>HTML</mark> for beginners.</p>
<p>Getting started with <mark>HTML</mark> in visual studi code</p>
```
![mark](mark.png)

## ```<small></small>``` for smaller text
Renders the enclosed text in a smaller font size relative to the surrounding text.  
Typically used for fine print, disclaimers, or any text that needs to be less prominent.  
```HTML
<p>This is <small>smaller</small> text.</p>
<p>This is personal work: 
    <small>All rights reserved, credits to the owner</small></p>
```
![Small](small.png)

## ```<del></del>``` for deleted text
Represents text that has been deleted or removed, usually rendered with a strikethrough.  
Used to show revisions, corrections, or updates in text, often seen in documents or collaborative writing.
```HTML
<p>This is <del>deleted</del> text.</p>
```
![deleted text](deleted_text.png)

## ```<ins></ins>``` for inserted text
This tag represents text that has been inserted into a document, usually rendered with an underline.  
Used to show additions or updates to a text.  
```HTML
<p>This is <ins>inserted</ins> text.</p>
```
![inserted text](inserted_text.png)

## ```<sub></sub>``` for subscript text
This tag renders the enclosed text as subscript, which appears smaller and lower than the surrounding text.  
Commonly used in chemical formulas, mathematical equations, or footnotes.  
```HTML
<p>This is H<sub>2</sub>O.</p>
```
![subscript](subscript.png)

## ```<sup></sup>``` for superscript text
This tag renders the enclosed text as superscript, which appears smaller and higher than the surrounding text.
```HTML
<p>This is E = mc<sup>2</sup>.</p>
```
![superscript](superscript.png)
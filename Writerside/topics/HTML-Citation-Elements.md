# HTML Citation Elements

HTML provides several elements specifically for quoting text, providing citations, abbreviating words, defining contact information, and handling bidirectional text.  
These elements help structure content in a meaningful and semantically appropriate way.  
Let's take a look at some of them:

## ```<blockquote></blockquote>``` for block quotations
Represents a section that is quoted from another source, typically displayed as a block of text that is indented from the rest of the content.  
Used for longer quotations, usually of multiple lines or paragraphs.
It takes in an attribute called ```cite``` which specifies the source of the quotation.
```HTML
<p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci, quibusdam necessitatibus suscipit nisi expedita ex consequatur! 
    Corporis, architecto iusto? Labore.
</p>
<blockquote cite="https://www.example.com/">
    This is a blockquote. It is typically used for longer quotations.
</blockquote>
<p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis laborum harum error sint dolores provident 
    deleniti beatae magni ipsum voluptates?
</p>
```
![blockquote](blockquote.png)

## ```<q></q>``` for inline quotes
Represents a short inline quotation, typically enclosed in quotation marks.  
Used for short quotes within a paragraph or sentence.  
It takes in an attribute called ```cite``` which specifies the source of the quotation.
```HTML
<p>
    As the saying goes, 
    <q cite="https://www.example.com">Actions speak louder than words</q>
    so we decided to do something
</p>
```
![q](q.png)

## ```<abbr></abbr>``` for abbreviations
Represents an abbreviation or acronym, with an optional title attribute to specify the full term.  
When the user hovers on the text wrapped with this attribute, a small title pops up with the full meaning of the abbreviated tag.  
```HTML
<p>
    The project repository <abbr title="Looks good to me">LGTM!</abbr>
</p>
```
![abbr tag](abbr.png)

## ```<address></address>``` for contact information
Provides contact information for the owner of a document or article, often displayed in italics.
```HTML
<p>Here's how you can reach us:</p>
<address>
    Send us an email to: info@company.com
</address>
<address>
    Call us: +254723190821
</address>
```
![address](address.png)

## ```<cite></cite>``` for citations
Represents the title of a work (such as a book, article, movie, etc.) or a reference to a source.  
Used to cite the source of a quote, idea, or referenced material, typically rendered in italics.  
```HTML
<p>One of my favorite books is <cite>Atomic Habits</cite> by James Clear.</p>
```
![cite](cite.png)

## ```<bdo></bdo>``` for overriding text direction
Overrides the current text direction, allowing you to change the direction of text display from left-to-right (LTR) to right-to-left (RTL), or vice versa.  
Used when embedding text in a language that uses a different writing direction, such as Arabic, within a document that has a different base direction.  
It takes in an attribute called ```dir``` which specifies the direction of the text. Values can be ltr (left-to-right) or rtl (right-to-left).
```HTML
<p>
    The word 
    <bdo dir="rtl">Hello world!</bdo> 
    is displayed in reverse and it is Hello world!
</p>
```
![bdo](bdo.png)

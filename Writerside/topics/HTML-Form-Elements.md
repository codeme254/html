# HTML Form Elements

An HTML form can contain one or more of the following elements:

## ```<input></input>``` element
It is used to create various types of fields for users to input their data.  
One of the most important attribute it takes is the ```type``` attribute which defines the type of input.  

```HTML
<form>
    <p>What is your name</p>
    <input type="text">
</form>
```
![Text input](text-input.png)

## ```<label></label>``` element
It is used to define a label for an input element.  
When a user clicks on a label, the associated input element gets focused.  
For this to work, the label element has a ```for``` attribute which we can pass to our own value, we then pass an id
attribute to the associated input element matching the for attribute of the label as shown.

```HTML
<form>
    <label for="first-name">first name</label>
    <input type="text" id="first-name">
    
    <label for="lastname">last name</label>
    <input type="text" id="lastname">
</form>
```
![label](label.png)

## ```<select></select>``` element
The select element is used to create a drop-down list.  
It is used together with the ```<option></option>``` elements to define the available options.
```HTML
<form>
    <label for="county">Select your county:</label>
    <select id="county">
        <option>Nairobi</option>
        <option>Nakuru</option>
        <option>Mombasa</option>
        <option>Eldoret</option>
        <option>Kirinyaga</option>
        <option>Murang'a</option>
    </select>
</form>
```
![select](select.png)

## ```<textarea></textarea>``` element
The textarea element is used for multi-line text input.  
It allows for larger amounts of text and spans multiple lines.  
```HTML
<form>
    <label for="about-user">Tell us about yourself:</label>
    <textarea id="about-user"></textarea>
</form>
```
![text area](text-area.png)

## ```<fieldset></fieldset>``` and ```<legend></legend>``` elements.
The fieldset element is used to group related elements, it visually groups content inside a form often with a border around it.
It is used with the legend element which defines a caption for the fieldset.
```HTML
<form>
    <fieldset>
        <legend>Personal information</legend>
        <label for="firstname">first name</label>
        <input type="text" id="firstname">
        <label for="lastname">last name</label>
        <input type="text" id="lastname">
    </fieldset>
    <fieldset>
        <legend>next of kin information</legend>
        <label for="fullname">full name</label>
        <input type="text" id="fullname">
        <label for="school">school</label>
        <input type="text" id="school">
    </fieldset>
</form>
```
![fieldset](field_set.png)

## ```<datalist></datalist>``` element
Used to provide a list of predefined options for an input element.  
Allows users to either type a value or select a value from a list.  
```HTML
<label for="browser">what browser do you use:</label>
<input list="browsers" id="browser">
<datalist id="browsers">
    <option value="Chrome">
    <option value="Firefox">
    <option value="Safari">
    <option value="Edge">
</datalist>
```
![datalist](data_list.png)
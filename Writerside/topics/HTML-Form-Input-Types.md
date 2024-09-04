# HTML Form Input Types

HTML has different types for ```<input>``` element.  
These types are defined using the type attribute and they include:

## Input type text
Defines a single-line text input field.
```HTML
<form>
    <label for="fname">first name</label>
    <input type="text" id="fname">
</form>
```
![text input](input_text.png)

## Input type number
Defines a number input field.
```HTML
<form>
    <label for="age">What is your age:</label>
    <input type="number" id="age">
</form>
```
![number](number.png)

## Input type email
It is used for input types that should contain an email address.  
Depending on the browser support, the email address will be automatically validated when submitted.  
```HTML
<form>
    <label for="email">What is your email address?</label>
    <input type="email" id="email">
</form>
```
## Input type password
Defines a password field.  
Most browsers will hide what the user is typing with bullets or any other symbol.  
```HTML
<form>
    <label for="password">type a password</label>
    <input type="password" id="password">
</form>
```
![password](password_1.png)
When the user starts typing the password, it will be hidden as shown:
![hidden password](password_2.png)

## Input type checkbox
Checkboxes let a user select zero or more options of provided choices.  
```HTML
<form>
    <p>What languages do you program in:</p>

    <label for="python">python</label>
    <input type="checkbox" id="python">
    
    <label for="javascript">javascript</label>
    <input type="checkbox" id="javascript">

    <label for="C">C</label>
    <input type="checkbox" id="C">

    <label for="c++">c++</label>
    <input type="checkbox" id="c++">

    <label for="go">go</label>
    <input type="checkbox" id="go">
</form>
```

![checkbox](checkbox_1.png)

The user can select multiple options
![checkbox](checkbox_2.png)

## Input type color
Used for color input.  
A color picker is usually shown up at the input field.  
```HTML
<form>
    <label for="favcolor">Select your favorite color:</label>
    <input type="color" id="favcolor">
</form>
```
![color](color.png)

## Input type date
Used for date input.  
A date picker is usually displayed in the input field.
```HTML
<form>
    <label for="birthday">Birthday:</label>
    <input type="date" id="birthday">
</form>
```
![date](date.png)

## Input type time
Used for time input.  
A time picker is usually displayed in the input field.  
```HTML
<form>
    <label for="checkin">What is the checkin time:</label>
    <input type="time" id="checkin">
</form>
```
![time](time.png)

## Input type file
Defines a file select field for file uploads.

```HTML
<form>
    <label for="profile-picture">Upload profile picture:</label>
    <input type="file" id="profile-picture">
</form>
```
![file upload](file-upload.png)

## Input restrictions and attributes
<table>
    <thead>
        <tr>
            <th>Restriction</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>checked</td>
            <td>Specifies that the input should be pre-selected when the page loads</td>
        </tr>
        <tr>
            <td>disabled</td>
            <td>Specifies that the input should be disabled</td>
        </tr>
        <tr>
            <td>max</td>
            <td>Specifies the maximum value for a number input field</td>
        </tr>
        <tr>
            <td>min</td>
            <td>Specifies the minimum value for a number input field</td>
        </tr>
        <tr>
            <td>maxlength</td>
            <td>Specifies the maximum number of characters for an input field</td>
        </tr>
        <tr>
            <td>readonly</td>
            <td>Specifies that the input field is readonly (cannot be changed)</td>
        </tr>
        <tr>
            <td>required</td>
            <td>Specifies that the input field must be filled out</td>
        </tr>
        <tr><td colspan="2">Attributes</td></tr>
        <tr>
            <td>placeholder</td>
            <td>Specifies a short hint that describes the expected value of an input field.</td>
        </tr>
        <tr>
            <td>autofocus</td>
            <td>Specifies that the input field should automatically get focus when the page loads.</td>
        </tr>
    </tbody>
</table>
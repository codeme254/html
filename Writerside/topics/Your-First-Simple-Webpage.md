# Your First Simple Webpage

Now that we have our [development environment](HTML-Development-Environment.md) ready, it is time to write our first HTML code.

### Step 1: Launch your code editor
The first thing is to launch the code editor you installed, this is where you will write and edit your HTML code.

### Step 2: Create a new HTML file
- In your code editor, select the option for creating a new file, this is usually under the 'File' menu ('File > New File') or by using a keyboard shortcut such as <kbd>CTRL + N</kbd> or <kbd>CMD + N</kbd> for mac.
- Name this file ```index.html``` and choose a folder/directory where you want to save it in your computer. It is important that you name this file ```index.html```.
> HTML files are saved with the extension ```.html```, this tells our computer that the file contains HTML code and could be opened by a web browser

> The file is named as ```index.html``` because web servers are configured to look for index.html file to serve to the visitors of our website when a file is not specified, for example, when a user visits www.example.com, since no file or path has been specified, index.html is served to the visitor.

### Step 3: Write your first HTML code
- In the index.html file open in your code editor, type the code below:
```HTML
<p>Hello, World. Welcome to my first webpage</p>
```

### Step 4: Open the HTML file in a web browser
- Navigate to the folder/director where you saved the index.html file.
- Double-click on the file, it will open in your default browser. Alternatively, you can right-click the file and select "Open with" (or a similar option depending on your platform) and then choose your preferred browser.  
- The content will be displayed in according to the HTML code you wrote in your file, for example:

![first html code output](first_html_code.png)

### Step 5: Edit and refresh
- Go back to your code editor and try editing the HTML file, let's add the line below as an example:
```HTML
<p>Hey mum, HTML is awesome.</p>
```
With this new line added, your file should look like:
```HTML
<p>Hello, World. Welcome to my first webpage</p>
<p>Hey mum, HTML is awesome.</p>
```
- After making these changes, save the file again by pressing <kbd>CTRL + S</kbd> or <kbd>CMD + S</kbd> or by using the save option of your code editor.
- Switch back to your browser and refresh the page (you can press <kbd>F5</kbd> or <kbd>CTRL + R</kbd>) or using your browsers refresh button or any similar option, you should see your changes reflected immediately.

![Changes Reflected](first_html_code_2.png)
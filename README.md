"# MERN-Task2" 
Window Object:
---------------
The window object represents the browser window or tab containing a web page. It is the global object in the browser environment, meaning all global JavaScript objects, functions, and variables are members of the window object. Here are some key points and functionalities of the window object:

Global Scope: Variables declared globally (outside any function) are properties of the window object.
Methods and Properties:
window.alert(): Displays an alert dialog.
window.confirm(): Displays a dialog with a message and OK/Cancel buttons.
window.prompt(): Displays a dialog with a message prompting the user to input some text.
window.location: Provides information about the current URL and methods to navigate to different URLs.
window.setTimeout(): Executes a function after a specified delay.
window.setInterval(): Repeatedly calls a function with a fixed time delay between each call.
Browser Control: Methods like window.open() to open new browser windows or tabs, window.close() to close them, and window.focus() to bring the window into focus.
Screen Information: Properties like window.innerWidth and window.innerHeight give the dimensions of the viewport.



Document Object:
----------------
The document object represents the HTML document loaded in the window. It is a property of the window object (window.document). The document object is the entry point to the content of the web page and allows for manipulation of the DOM (Document Object Model). Here are some key points and functionalities of the document object:

DOM Manipulation:
------------------
document.getElementById(): Retrieves an element by its ID.
document.getElementsByClassName(): Retrieves elements by their class name.
document.getElementsByTagName(): Retrieves elements by their tag name.
document.querySelector(): Retrieves the first element matching a CSS selector.
document.querySelectorAll(): Retrieves all elements matching a CSS selector.
Content Access and Modification:
document.createElement(): Creates a new HTML element.
document.createTextNode(): Creates a new text node.
document.appendChild(): Appends a child node to a parent node.
document.removeChild(): Removes a child node from a parent node.
document.innerHTML: Gets or sets the HTML content inside an element.
Document Metadata:
document.title: Gets or sets the title of the document.
document.URL: Returns the complete URL of the document.
document.cookie: Gets or sets the cookies associated with the document.
Summary
Scope:
window: Represents the browser window or tab.
document: Represents the HTML content of the page.
Main Use:
window: For browser-level interactions and global properties/methods.
document: For manipulating and accessing the content of the webpage.
Hierarchy:
window is the global object, and document is a property of window.
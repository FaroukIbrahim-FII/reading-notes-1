# Read: 09 - Forms and Events

# HTML :

### `<form>` element : is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.
* action attribute : specifies where to send the form-data when a form is submitted.
*  method attribute : specifies how to send form-data (the form-data is sent to the page specified in the action attribute),The form-data can be sent as URL variables (with `method="get"`) or as HTTP post transaction (with `method="post"`).

#### The form deals with the back-end in order to process any entry, order or value that takes place through the front-end, by communicating with it and transferring any information, entrance, values, or commands, and the Back-end in its role is dealing with the Database and Process commands if necessary, finally any processing output is returned to the front-end.

* `<input>` element : is the most used form element , To take the input from the user, can be displayed in many ways, depending on the type attribute : type="text/radio/checkbox/submit/button/password" .
* `<textarea>` element : is used to create a mutli-line  text input.
* `<select>` : drop-down list .
* `<input type="file">` : defines a file-select field and a "Browse" button for file uploads.
* `<input type="image">` : defines an image as a submit button.
* `<input type="hidden">` defines a hidden input field.
* `<fieldset>` : tag is used to group related elements in a form.
* `<legend>` : tag defines a caption for the `<fieldset>` element.
* `<input type="date">` : defines a date picker.
* `<input type="email">` : defines a field for an e-mail address.
* `<input type="url">` : defines a field for entering a URL.
* `<input type="search">` defines a text field for entering a search string.

Ex :
```HTML
<form action="URL" method="get/post">
	<input type="text/radio/checkbox/submit/button/password">
	<textarea >Enter text here . . . </textarea>
	<select >
  		<option value="...">Enter text here . . . </option>
  		<option value="...">Enter text here . . . </option>
	</select>
	<input type="file">
	<input type="image" src="URL" alt=". . .">
 	<input type="hidden">
	<input type="date">
	<input type="email">
	<input type="url">
</form>
```


# CSS :

* `list-style-type` : specifies the type of list-item marker in a list : none/disc/circle/square/decimal/decimal-leading-zero/lower-alpha/upper-alpha/lower-roman/upper-roman .
* `list-style-image` : property replaces the list-item marker with an image : Ex `list-style-image: url('URL');`.
* `list-style-position` : property specifies the position of the list-item markers : Ex `list-style-position: outside/inside;`.
* `list-style` : property is a shorthand for the following properties: `list-style-type`,`list-style-position`,`list-style-image`: EX `list-style: square inside url("URL");`.
* `:hover` : selector is used to select elements when you mouse over them : Ex `tagName :hover { css declarations;  }`.
* `empty-cells` : property sets whether or not to display borders on empty cells in a table : Ex :`empty-cells: hide;`.
* `border-spacing` : property sets the distance between the borders of adjacent cells.
* `border-collapse` : property sets whether table borders should collapse into a single border or be separated.
* `cursor` : property specifies the mouse cursor to be displayed when pointing over an element : Ex `cursor: auto/crosshair/default/pointer/move/text/wait/help/url("URL");`.

# JAVASCRIPT :

### When JavaScript is used in HTML pages, JavaScript can "react" on these events, event can be something the browser does, or something a user does . some examples  events : web page has finished loading, input field was changed, button was clicked.

### Often, when events happen, you may want to do something , JavaScript lets you execute code when events are detected, HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

### HTML DOM Events : Events are normally used in combination with functions, and the function will not be executed before the event occurs.To learn about their types and more about them, see the attached : [ DOM Events ]( link:https://www.w3schools.com/jsref/dom_obj_event.asp ) .


### Event listeners : are a more recent approach to handling events. They can deal with more than one function at a time. To learn about their types and more about them, see the attached : [ Event listeners ]( https://www.w3schools.com/js/js_htmldom_eventlistener.asp  ) .


### INTERFACE EVENTS : User interface (UI) events occur as a result of interaction with the browser window rather than the HTML page contained within it,  e.g., a page having loaded or the browser window being resized. Ex : load, unload, error ,resize ,scroll .

### MOUSE EVENTS : Events that occur when the mouse interacts with the HTML document belongs to the MouseEvent Object. To learn about their types and more about them, see the attached : [ MOUSE EVENTS ]( https://www.w3schools.com/jsref/obj_mouseevent.asp ) .


### KEYBOARD EVENTS : Events that occur when user presses a key on the keyboard, belongs to the KeyboardEvent Object. To learn about their types and more about them, see the attached : [ KEYBOARD EVENTS ]( https://www.w3schools.com/jsref/obj_keyboardevent.asp ) .

[ Back To README !]( https://yousefabujalboush.github.io/reading-notes/ )
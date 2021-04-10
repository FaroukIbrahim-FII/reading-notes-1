# Read: 06 - JS Object Literals; The DOM

## Objects group together a set of variables and functions to create a model.

### VARIABLES BECOME KNOWN AS PROPERTIES, FUNCTIONS BECOME KNOWN AS METHODS.

#### Ex : 
```JAVASCRIPT
var objectName = {
	 properitesName : ..... ,
  	 methodsName : function (){
		// code ... ;
	}
};

// call Objects 

... = objectName.properitesName;
... = objectName['properitesName'];
... = objectName.methodName();
```

### With the HTML DOM, JavaScript can access and change all the elements of an HTML document.

#### as a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers’ memory, document node is added; it represents the entire page (and also corresponds to the document object ,to access the DOM tree, you start by looking for elements. Once you find the element you want, then you can access its text and attribute nodes if you want to.

### METHODS THAT RETURN A SINGLE ELEMENT NODE :
* `document.getElementById(elementID)` - returns the element that has the ID attribute with the specified value.
* `document.querySelector(".example")` - returns the first element that matches a specified CSS selector(s) in the document.
* `document.getElementsByClassName("example")` - returns a collection of all elements in the document with the specified class name, as an HTML Collection object.
* `document.getElementsByTagName("div")` - returns a collection of all elements in the document with the specified tag name, as an HTMLCollection object.
* `document.querySelectorAll(".example")` - returns all elements in the document that matches a specified CSS selector(s), as a static NodeList object.

#### When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element).

#### Nodelists look like arrays and are numbered like arrays, but they are not actually arrays; they are a type of object called a collection.

### DOM working with the node not with element directly,some methods to work with node and update content:
* `nodeValue`
* `create Element() `
* `createTextNode() `
* `appendChild() / removeChild() `
* `hasAttribute() `
* `getAttribute() `
* `setAttri bute() `
* `removeAttribute() `

#### Nodelists(live Nodelist,static Nodelist) look like arrays and are numbered like arrays, but they are not actually arrays; they are a type of object called a collection.

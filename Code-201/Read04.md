# Read: 04 - HTML Links, CSS Layout, JS Functions

# HTML

#### `<a>` : creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address. Content within each `<a>` should indicate the link's destination.
#### target attribute as `target="_blank"` : open link in a new window .
##### Ex :
~~~~
<a href="hyperlink/web pages/email addresses/locations in the same page"> . . . </a>
<a href="https://www.google.com/">google</a> <!-- hyperlink -->
<a href="About-me.html">About-Me</a> <!-- Same Folder -->
<a href="home/About-me.html">About-Me</a> <!-- Child Folder -->
<a href="project/home/About-me.html">About-Me</a> <!-- Grandchild Folder -->
<a href="../About-me.html">About-Me</a> <!-- Parent Folder -->
<a href="../../About-me.html">About-Me</a> <!-- GrandParent Folder -->
<a href="mailto:yousef.y.jalboush@gmail.com">yousef.y.jalboush@gmail.com</a> <!-- Email Links -->
<a href="#mySection">Arc Shot</a> <!-- locations in the same page , The href here belongs to the tag containing this id -->
<a href="About-me.html#mySection"> Click here </a> <!-- locations in the another page -->
~~~~

# CSS 

#### Block elements : start on a new line Ex: `<h1> ,<p> ,<ul> ,<li>`.

#### Inline elements : flow in between surrounding text Ex: `<img> ,<b> ,<i>`.

#### Containing : block element sits inside another block element.

#### we can control the postion of the elements and the layout of the page there are alot of types of  positioning schemes south as Normal flow ,Relative Positioning ,Absolute positioning.

#### To determine where is box postion through boxoffset properties there is Fixed Positioning ,Floating Elements.

#### To control which box have the priority to appear : z-index.

# Js

### WHAT IS A FUNCTION : Functions are "self contained" modules of code that accomplish a specific task , it can be used over and over and over again. Functions can be "called" from the inside of other functions.

##### Ex :
~~~~
function sayHello(parameter1, parameter2, ......){
	block of code ....
	return val ;  // Return value
}

var sayHello = function(parameter1, parameter2, ......) { 
	block of code ....
	return val ;  // Return value
} ; 

let hello = sayHello( parameter1, parameter2, ...... ); //Calling Function
~~~~



#### How does pair programming work? pair programming commonly involves two roles: the Driver and the Navigator. 
* The Driver is the programmer who is typing code.
* The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture.

##### we use pair programming  because it is very useful when we want to build our project such as save time and  reduse the error in this way we write the code in great efficiency.
##### pair programming is Increase cooperation  in this way the persentage of the error will be low , learing from each other becuase everyone of them have specific skills,It is based on increasing the skill of communication because it needs to always speak with the other party in the project clearly, thus increasing your skills in speaking and communicating ideas, also based on training you to prepare on the work environment because most of them consist of more than one person, not one person.



[ Back To README !]( https://yousefabujalboush.github.io/reading-notes/ )
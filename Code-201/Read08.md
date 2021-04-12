# Read: 08 - More CSS Layout

### layout is the way that we control the structure of the webpage that mean where the element should be to create creative web design.

### Block elements : start on a new line Ex: `<h1> ,<p> ,<ul> ,<li>`.
### Inline elements : flow in between surrounding text Ex: `<img> ,<b> ,<i>`.
### Containing : block element sits inside another block element.

* `z-index` : property specifies the stack order of an element.
* `position` : property sets how an element is positioned in a document. The top, right, bottom, and left properties determine the final location of positioned elements.
    - `position: static ;` positioned elements are not affected by the top, bottom, left, and right properties.
    - `position: relative ;` is positioned relative to its normal position.
    - `position: absolute;` is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).
    - `position: fixed;` is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled.
* `float` : property is used for positioning and formatting content e.g. let an image float left to the text in a container.
* `clear` : property specifies what elements can float beside the cleared element and on which side.

### we can from css control the webpage how is going to show becuase there are different sizes for the screen even the resolution is different from type to other type of device.
# Building Blocks

CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.
Block-level elements
start on a new line
Examples include:
<h1> <p> <ul> <li>
Inline elements
flow in between
surrounding text
Examples include:
<img> <b> <i>
### Containing Elements
**If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.**
* It is common to group a number of elements together inside a <div>
(or other block-level) element. For example, you might group together
all of the elements that form the header of a site (such as the logo and
the main navigation). The <div> element that contains this group of
elements is then referred to as the containing element. *
## Controlling the Position of Elements
** Normal flow
Every block-level element 
appears on a new line, causing 
each item to appear lower down 
the page than the previous one. 
Even if you specify the width 
of the boxes and there is space 
for two elements to sit side-byside, they will not appear next 
to each other. This is the default 
behavior (unless you tell the 
browser to do something else). **

**Relative Positioning
This moves an element from the 
position it would be in normal 
flow, shifting it to the top, right, 
bottom, or left of where it 
would have been placed. This 
does not affect the position of 
surrounding elements; they stay 
in the position they would be in 
in normal flow**

*Absolute positioning
This positions the element 
in relation to its containing 
element. It is taken out of 
normal flow, meaning that it 
does not affect the position 
of any surrounding elements 
(as they simply ignore the 
space it would have taken up). 
Absolutely positioned elements 
move as users scroll up and 
down the page*

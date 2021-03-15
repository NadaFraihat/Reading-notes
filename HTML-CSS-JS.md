# Lists
HTML provides 3 ways to write a list:
1. Ordered lists **< ol>** used numbers
2. Unordered lists **< ul>** used bullets.
3. Definition lists **< dl>** used to define terminology.
For ordered and unordered lists, we use **< li>** for each item we mention.
For defention lists, we use **< dt>** to contain the term which we are going to define, and **< dt> to 
descripe it.

* We can make a lists inside a list, just bu write a new < li> tag between it, and It's called **nested list**.
*Example:*
< html>
<head></head>
<body>
< ol>
< li>
Front end developer
< li>
HTML
< /li>
< li>
CSS 
< /li>
< /li>
< li>
Back end developer
< /li>
< /ol>
</body>

# Boxes
By default a box is sized just big enough to hold its contents. 
To edit your box's dimensions use **width and height attributes**.
* We can use **Pixel, percentage or ems** for dimensions.
1.  Pixel, the element will be related to the page.
2. Percentage for the the size of the box is relative to the size of the browser window or if the box is encased withinanother box.
3. ems the size of the box is based on the size of text within it.

## Limiting Width

1. min-width 
2. max-width
These are very helpful properties to ensure that the content of pages are legible (especially on
the smaller screens of handheld devices).

## Overflowing Content
The overflow property tells the browser what to do if the content contained within a box is larger
than the box itself.
**< overflow>**
It has many choices:
1. scroll
2. hidden
3. auto

## Border, Margin & Padding
1. Border: every box of my HTML has a border,The border separates the edge of one box from another.
   It's attributes:
   + border-width
   + border-style
   + border-color
2. Padding:Padding is the space between the border of a box and any content contained within it.
   +The value of this property is most often specified in pixels
3. Margin: You can set the width of a margin to create a gap between the borders of two adjacent boxes.


## Centering Content
1. left-margin/right-mrgin auto: to center a box on the page (or center it inside the element that it sits in), you
2. text-align: to set the text at the center of it's box

## Inline/Block
**< display>**
1. Inline:This causes a block-level element to act like an inline element.
2. Block: This causes an inline element to act like a block-level element.
3. inline-block: This causes a block-level element to flow like an inline element,but looks like block.
4. none: It's act as though it is not on the page.
* Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.

## Hiding Boxes
**< visibility>**
1. hidden: hide the element
2. visible: visible the element

# **CSS3** 
## Border Images
**< border-image>**
*The border-image property applies an image to the border of any box.*
It requires 3 pieces:
1. URL of the image
2. Where to slice the image
3. What to do with the straight edges:
   + stretch
   + repeat
   + round
## Box Shadows
**< box-shadow>**
The box-shadow property allows you to add a drop shadow around a box. 
It works just like the text-shadow property.
1. Horizontal offset: Negative values position the shadow to the left of the box.
2. Vertical offset: Negative values position the shadow to the top of the box.
3. Blur distance: If omitted, the shadow is a solid line like a border.
4. Spread of shadow

## Rounded Corners
**< border-radius>**
You can also use a shorthand of these four properties (in clockwise order: top, right,
bottom, left). For example:
border-radius: 10px, 20px, 5px, 10px;


# JS 
## Basic JavaScript Instructions
### Arrays
*An array is a special type of variable. It doesn't just store one value; it stores a list of values.*
**Example:**
var usersAge;
usersAge=[ 23,20,30,28];
* The values are assigned to the array inside a pair of square brackets, and each value is separated by a **comma**.
* The values in the array do not need to be the same data type.
### VALUES IN ARRAYS 
+ Values in an array are accessed as if they are in a numbered list. It is important to know that the
numbering of this list starts at **zero**
Who to enter a value in the array?
1. Each item in an array is automatically given a number called an index
2. Confusingly, index values start at 0 
**Example:**
var usersAge;
usersAge=[ 23,20,30,28];
*23 has i=0, 20 has i=1, 30 has i=2, 28 has i=3.*
*So if you want to catch 30, call it by userAge[ 2]*


## Decisions and Loops

### SWITCH STATEMENTS 
The switch statement is used to perform different actions based on different conditions.

**Syntax:**
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block

*This is how it works:*
1. The switch expression is evaluated once.
2. The value of the expression is compared with the values of each case.
3. If there is a match, the associated block of code is executed.
4. If there is no match, the default code block is executed.

### TYPE COERCION & WEAK TYPING 
If you use a data type JavaScript did not expect, it tries to make sense of the operation rather than report an error.

### TRUTHY & FALSY VALUES 
Due to type coercion, every value in JavaScript can be treated as if it were true or false; and
this has some interesting side effects. 
**Falsy**
*values are treated as if they are fa 1 se. The table to the left shows a hi ghScore variable with a series of values, all of which
are falsy.*
**Truthly**
 *values are treated as if they are true. Almost everything that is not in the falsy table can be treated as if it were true.*
* All values evaluate to either truthy or falsy. 

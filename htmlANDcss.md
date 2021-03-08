# CSS
It is a cascading style sheet, which can make the browser more styish with colors and arrange the elements.


## How to creat CSS page?
+ Make a new file with **.css** extension
+ Link it with your html page by write between the head tag the following sentence:
  **<link href="nameoffile.css" type="text/css rel="stylesheet">**
  where as 
  * rel:This specifies the relationship between the HTML page andthe file it is linked to.
  * type: This attribute specifies the type of document being linked to. 
  * href : the path of the file
The previous way called **external css**
**internal css:**
between the head tag, you can add a style tag and write your code of css between the brackets.
<style type="text/css">
 body {
 font-family: arial;
 background-color: rgb(185,179,175);}
 h1 {
 color: rgb(255,255,255);}
 </style>

 **But if you have multi pages, you have to use external way**
 



## How does it work?
 tag-name {
 attribute: value;}
As the tag-name is selector, and between culy brackets is the declaration.
You can write as many as you want of attribute inside the brackets.
**Keep in mind** CSS selectors are case sensitive.

## Selectors:
1. Univirsal selectors: apply to all the elements inside the page.
such:
*{}
2. Type Selector: Matches element names
such: h1, h2, h3 {}
3. Class Selector: Matches an element whose class attribute has a value that matches the one specified after
the period **(or full stop)** symbol
such:
 p.note {}
 or
 .note {}

And many ways to call the elemet and style it.

# Color and background-color Attributes
Color not only brings your site to life, but also helps convey the mood and evokes reactions

1. rgb values: red,green,blue and its between 0 and 255. 
2. hex code: These are six-digit codes that represent the amount of red, green and blue in a color,
preceded by a pound or hash # .
3. color names

## contrast
It is important to ensure that there is enough contrast between any text and the background color.
Developers added a new attribute which is RGBA, to edit the contrast of the color.







# How do I write a script?
Web developers usually talk about **three** languages that are used to create web pages:
1. HTML
2. CSS
3. JavaSrcipt
We keep each of them in seperated file, Each language forms a separate layer with a different purpose. 

## HTML
focusing on the most important thing about your site: **its content**.
## HTML+CSS 
Adding the CSS rules in a separate file keeps rules regarding how the page **looks** away from the content itself 
## HTML+CSS+JAVASCRIPT 
 JavaScript is added last and enhances the usability of the page or the experience of **interacting** with the site. 

 ### Creating JS 
 1. Creat a file and open it with any code editor you want
 2. Creat javascript page, with .js extension
 3. each of HTML,CSS,JAVASCRIPT and Images must has it's own folder.
 
 ### Linking JS
 By write <script src='name-of-js-folder.js'></script>, you can link the code of js with HTML page.
 You must write this link before the closing tag of **body**

 ### How to use Methods and objects
 We have many of methods for JS ,example:
 1. document.write('') which display the content you wrote at the window of the browser
  where **document**  is the object
  **.write('')** is the method
  **('')** is the parameter

### Statements 
A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon. 
1. If statement 
**if** (**condition**) {
statement ;}
**else if** (**condition**) {
statement;}
**else** {
statement;}
*KEEP IN MIND* you can write as much as you want of **else if** statement.

2. Comment
To create a single line comment in JavaScript, you place two slashes "//" in front of the code or text you wish to have the JavaScript interpreter ignore. When you place these two slashes, all text to the right of them will be ignored, until the next line.

3. Variables
It is a container with temporarily store the bits of information it needs to do its job. 
It can store this data in variables. 
#### How to declare them?
var name-of-your-var ;
#### How to assgin them?
var name-of-your-var = value;
you can write boolen, string or number as variable value

After we create a new web page with JS, we had an interactive page
We can put the code of js between the script tags and with it's own file, and it has the same result.
**But** perfering to put the code in the JS file.

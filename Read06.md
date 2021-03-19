# Problem domain
## What is problem domain?
*A problem domain is the area of expertise or application that needs to be examined to solve a problem.*
**Problem Domain** is anything and everything that is needed to define the area under analysis, fully understand the inputs and outputs of its processes, and achieve the goals of the area under analysis, but nothing more.

## What is the hardest thing about writing code?
+ Learning a new technology
+ Naming things
+ Testing your code
+ Debugging
+ Fixing bugs
+ Making software maintainable
 *The single hardest thing about programming is learning the problem domain.*
 Writing code is a lot like putting together a jigsaw puzzle. 
 We put together code with the purpose of building components that we have taken out of the “bigger picture” of the problem domain.
 **But** Programming is easy if you understand the problem domain!
If understanding the **problem domain** is the hardest part of programming and you want to make programming easier, you can do one of two things:
1. Make the problem domain easier
2. Get better at understanding the problem domain

# Objects
## What is an object?
It is a group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.
**VARIABLES** BECOME KNOWN AS **PROPERTIES.**
Such as name of hotel, number or room it has.
**FUNCTIONS** BECOME KNOWN AS **METHODS.**
Such as checking how many rooms are remaining by subtracting the number of
booked rooms from the total number of rooms.
The following code shows us an example of **object** where It has 5 properties and and one method.
The **object** is in curly braces. It is stored in a variable called hotel.
var Hotel = {
name ='Nada',
room#=23,
booked=25,
gym: true,
roomTypes:['twins','double','suit'],
checkAvailability: function (){
    return this.rooms-this.booked;
}
}
Where (name,room,booked,gym,roomType,checkAvailability) are keys and (Nada,23,25,true,the array,function (){
    return this.rooms-this.booked;) are values.
Hotel is the **object.**

  ![Image](img/img1.PNG)
Key can be string, array, boolean ,number.
Value can be function.

### How to write an object?
1. use var/let to define the name on the object
2. name the object and use Upper case to first letter *Hotel.*
3. write = and curly brackets 
4. write the property that you want following by it's value *name:'Nada'.*
5. separate the keys using colon ','.
6. make your function ' checkAvailability: function (){}.

## How to access object?
*By using dot notation.*
Using the name of object followed by period then the name of property or method.
This known as **dot notation.**
Exalmpe:
var hotelName=hotel.name;
var roomFree=hotel.checkAvailability();


# Document object model (DOM)
*specifies how browsers should create a model of an HTML page and how JavaScript can access and update the*
*contents of a web page while it is in the browser window.*
**DOM** is neither part of HTML nor part of javascript. It is a separate of set rules.
It covers two primary areas:
1. MAKING A MODEL OF THE HTML PAGE
2. ACCESSING AND CHANGING THE HTML PAGE
**DOM tree**  IS AMODEL OF A WEB PAGE.
As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes.
Body of HTML:
![Image](img2/PNG)
Tree of DOM:
![Image](img3/PNG)

We can access the element inside tag by call it:
### Select an indiviual element node:
1. getEementById('')
2. querySelector()
### Select multi elements:
1. getElementByClassName('')
2. getElementByTagName('')
3. querySelectorAll()
### Trasvering between elements:
1. parentNode
2. previousSibling / nextSibling
3. firstChild / lastChild

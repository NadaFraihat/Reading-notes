# Tables
*A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.*

Each block in the grid is referred to as a **table cell**.
In HTML a table is written out row by row.
The following elements are required to make a table:
1. < table> < /table>
It is used to create a table. The contents of the table are written out row by row.
2. < tr>< /tr>
It indicates to table row, used to make a row for the table.
3. < td>< /td>
It indicates to table data, used to make a column for the table.
4. < th>< /th>
It indicates to table head, used to create a heading for the table.

## Spanning 
We can merge/span rows and coloumns by using an span attribute.
+ To span coloumns: colspan='# of columns'
+ To span rows: rowspan='# of rows'

## Long Tables
To distinguish between the contents of the table, we use the following elements:
1. < thead>< /thead>
2. < tbody>< /tbody>
3. < tfoot>< /tfoot>
# Functions, Methods, and Objects
The **new** keyword and the **object constructor** create a blank object.


![Image](Images/Capture6.PNG)
## Updating Object
To update a value of properties, we use dot notation or square brackets.


![Image](Images/Capture7.PNG)

+ To delete a property, we use **delete** keyword, as following:

![Image](Images/Capture8.PNG)


## CREATE THE OBJECT, THEN ADD PROPERTIES & METHODS
In both of these examples, the object is created on the first line of the code sample. The properties and methods are then added to it afterwards.


LITERAL NOTATION              |  OBJECT CONSTRUCTOR NOTATION
------------------------------| ----------------------------
![Image](Images/Capture9.PNG) | ![Image](Images/Capture10.PNG)
![Image](Images/Capture11.PNG)|![Image](Images/Capture12.PNG)


## STORING DATA
*In JavaScript, data is represented using name/value pairs.*
To organize the data, we can use an **array or object** to group a set of related values.
 In arrays and objects the name is also known as a **key.**

 + Variables has only one key, Array can store multiple pieces.
 + To retrieve the value of a variable, use its name.
 + To retrieve an item, use its index number.
 **Note** that each key in the object must be unique.

 ## Arrays
 Arrays are special types of object, but the key is index number.

 ![Image](Images/Capture13.PNG)


 ## THE WINDOW OBJECT
The window object represents the current browser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser.
Such as:

 ![Image](Images/Capture14.PNG)

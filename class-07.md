# tables 
**html table**:HTML tables are used for displaying data that make sense in spreadsheet software. They consist of rows and columns and are often used on websites for the effective displaying of tabular data
 HTML tables should be used for tabular data — this is what they are designed for. ... Because tables are not the right tool for layout
A table is defined using the <table> element
 and contains a number of table cells ( <td>, for “table data” ) which are organized into table rows  <tr> The markup HTML code for a table is always based on rows, never columns.
Table cells can be merged using the colspan and rowspan attributes.
Tables can be broken into sections using the following elements:
<thead> — Table header
<tbody> — Table body
<tfoot> — Table footer
ex:
<table> 
<tr> 
<th>Name</th>
<th>Favorite Color</th>
</tr> <tr> <td>Bob</td>
<td>Yellow</td> </tr> <tr> 
 <td>Michelle</td> <td>Purple</td> 
</tr>
    </table>
In JavaScript, an object is data, with properties and methods.
var message="Hello World!";

All objects in JavaScript descend from the parent Object constructor. Object has many useful built-in methods we can use and access to make working with individual objects straightforward. Unlike Array prototype methods like sort() and reverse() that are used on the array instance, Object methods are used directly on the Object constructor, and use the object instance as a parameter. This is known as a static method
###  Object.create()
The Object.create() method is used to create a new object and link it to the prototype of an existing object
### Object.keys()
Object.keys() creates an array containing the keys of an object.
const employees = {
    boss: 'Michael',
    secretary: 'Pam',
    sales: 'Jim',
    accountant: 'Oscar'
}
const keys = Object.keys(employees);
The Object.entries() method will only return the object instances own properties, and not any properties that may be inherited through its prototype.
Sometimes we need a "blueprint" for creating many objects of the same type.

The way to create an "object type", is to use an object constructor function.
example:
var myFather = new Person("John", "Doe", 50, "blue");
var myMother = new Person("Sally", "Rally", 48, "green")
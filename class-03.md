#Lists
there are 3 types of lists
1. Orderd lists: which every item in the list is numberd
1. Unorderlist:all the lists taht begin with bullet point
1. Definition lists:are made with sets of terms and the definition you create
example in tags
`<ol>`:is used for order list you can type to begin with character or a number 
`<ul>`:is used to print list items that start with bullet point
`<dl>`:consists of a series of terms and their definitions.
`<dt>`:This is used to contain the term being defined (the definition term). 
`<dd>`:This is used to contain the definition
### Nested list:you can put a nested list inside a list item
example:
<nav>
<ul>
<li>catagory
<ul>
<li>computers<li>
<li>phones</li>
<li>tablets</li>
<ul>
</li>
<li>about us </li>
<li> conatct us</li>
<li>gallery</li>
</ul>
</nav>
# Boxes
**Width & Height**
> specify the size of a box are to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size.
`min-width`: specifies the smallest size a box can be displayed at when the browser window 
`max-width`:indicates the maximum width a box can stretch to when the browser window is wide.
`overflow:tells the browser what to do if the content that is container is larger than
box its self.
`overflow`:hidden':hides any extra content that doesnt fit in the box
`overflow`:scroll':adds a scroll bar to the web page
# Margin ,Border,Paddding
`margin`: are used to create space around element
`padding`:are used to generate space around an element's content
`border`:allow you to specify the style, width, and color of an element's border.
> in border margin paddign theres always a coordinates
-top
-right
-bottom
-left

### borders proprties
1. border-width:the width of border it can by pixels or precentage or other units
1. border-color:the color of the border
1 .border-type:dashed/dotted/solid/double/etc..

### display
`inline`: a block-level element to act like an inline element.
`block`:inline element to act like a block-level element.
`inline-block`:This causes a block-level element to flow like an inline element, while retaining other features of a block-level element
`none`:this dont display elements on the page.
Q)  how to show and hide elements?
A)using visibality hidden or  visable
#conditions and loops
`If statements` - If a condition is true, then run the code in that block
`If else statements` - If a condition is true, then run the code in that block Otherwise, run the code in the else block.
`For loops` - Run the code in this block based on a set number of iteration This is known.
`While loops` - Run the code in this block while a condition is true The number of iterations is unknown.
example on if statment
ex:
var pass=50;
var mark=window.prompt("whats your mark");
if (mark >=pass)
{
    console.log("you have passed the exam");
}
example on if else statment:
if (typeof n == "string") {
 
} else {
    alert("function Employer requires a string");
    throw new Error("function Employer requires a string");
}
example on  nested ifelse
     var no = prompt("Enter a Number to find Odd or Even");
          no = parseInt(no);
          if (isNaN(no))
          {
               alert("Please Enter a Number");
          }
          else if (no == 0)
          {
               alert("The Number is Zero");
          }
          else if (no % 2)
          {
               alert("The Number is Odd");
          }
          else
          {
               alert("The Number is Even");
          }
example on do while:
     var i = 0;
     do
     {
          document.write(i+"<br>")
          i++;
     }
     while (i <= 5)
     example on for loop:
     var cars = ["BMW", "Volvo", "Saab", "Ford"];

for (i = 0, i <=> cars.length, ; i++) {
  console.log(cars[i])+ "<br>";
}




# TEXT 
- there are 2 types of markup
1. Strctural markup:elements that describe both elements and pargaphs
1. Semantic markup:its  a way of writing and structuring your HTML  so that it reinforces the semantics, or meaning also it provide extra information on the website.
## in HTML theres Headings
`<h1>`:is the largest heading.
`<h2>`: is for subheading.
`<h3>`: its smaller than h2..etc to h5.
> ps:`<h1>` is the largest heading  and `<h6>` is the smallest.
`<p>`: its a block of text or strcural any structural grouping of related content, such as images.
`<b>`: refred to bold  its block of text that can be represent in another visual way.
`<i>`:refred to italic  its block of text that can be represent in another visual way.
`<br>`: it will automatically show each new paragraph or heading on a new line.
<`hr>`: adding horzntial rule between elements
`<strong>`:indcates the tag element has a strong importance
`<blockqoute>`:The blockquote element is used to indicate the quotation of a large section of text from another source.
`<q>`:is used to write short text that has less charcters than pargraph.
`<abbr>`: element is used along with a title attribute to associate a full-text explanation
`<cite>`: tag defines the title of a work

#Introduction to Css
- Block element : that look they start on new line example:`<h1>`,`<p>`,`<div>`
-in-line element they flow with text and they dont start a new line `<img>`,`<b>`,`<i>`,`<span>`
**CSS Rules**
css rules contains tow parts
-Selector
-Decleration
### in every css declearion we have 2 things
-property 
-value 
### How we can use css on our webpage?
-external:we use an external css file and link it ex:> <link rel="stylesheet" href='name of the file'>
-internal:we use the `<style>` tag inside the head
-inline-block:we use inside an element and we dont recommend that way beacse i fi want to change 15  elemnts 
it will take alot of time and my page wont be orgnaized.

## Css Selectors
1. universal Selector:`*` it will change all the elements in the page
2. class Selector:`.` it target more than one class .
3. ID class:`#` it target only one spesfic element 
4. descendant selector:matches the element that is descendant from other element ex:> nav ul li a
> info:the css do overwriting when u write daplicate css and it will take the last value u entered


# basic of javascript
**Scripts**:script is series of instruction that the computer fallow in order to achieve a goal.
Q1)before you write your javascript what thing you need to do ?
1. try to state your goal of the script you are using
2. break Down your problem to make it easier to solve
> Each invidual instruction and step are called **Statment** also statment can be orgnaized in block statment.
theres 2 types of comments
-single-line-comment:`//`
-multi-line-comment:`/**/`

Q2) what is a variable?
*variable**:is a script that can store bits of information and use anywhere in the website.


Q3)how to Declare a variable?
ex:
>let a=5; or var=10; you can choose the type of value and store it in variable.
Q4)what Data types used in javascript?
1. number
2. float
3.boolean
4. object 
5. Strings



Q5)what is the rules of naming variables
A)it must begin with a character or _ and you cant use numbers or special symbols at the beginning of a variable and best practice to use camel case.
# Array
so what is an array
**Array**:is a special type of variable that can store a list of values.



Q6)how to define arrays
ex:
`var food=['cheese','spagtti','ice-cream'];`   
` var family=new Array('isam','alaa','omar','assem');`
# Conditions and For loops
>we use a lot of conditions like if ifelse switch turnry operator that a determince which code block can
be executed.


Q7)what are the conditions to execute a deccison 
-experssion is evluated and it must return a true value
-you need to write the correct syntax for the condition that are you using
**comperssion operators**
`==`:means that if its equal a value
`!=`:if its not equal the value
`===` if its equal the value and the type of the variable
# IF statment 



Q8)how IF statment works?
A)  IF statment eveluates or checks if the value true it execute the block code other wise
it execute the else block code
>info:we can use ifelse to have more than one condition
**For loop**
forloop:  is a control flow statement for specifying iteration, which allows code to be executed repeatedly

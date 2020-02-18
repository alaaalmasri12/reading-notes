# Link
so what is links?
-links:is web feature that allow us to move from one page to another
enabling the idea of surfing.
> links are created using the `<a>` linking the page using `href` propery:
ex:
> <a href="http://facebook.com">facebook</a> 
note:when you link to a website you use absoloute URLs **relative site** can be used when linking to pages within your own website 
>If your site is organized into separate folders or directories you need to tell the browser how to get from the page it is currently on to the page that you are linking to.
Relative link types
same folder for example `<a href="conact.html">Contact</a>`
child folder for example    `<a href="videos/vedioe.html">`
grandchild folder for example `<a href="201/reading-notes/class-04.html">`
>parent folder to back one step in the dicrctory you are in
for example `<a href="../index.html">Home</a>`
### Email links

`mailto:` To create a link that starts up the user's email program and addresses an email to a specified email address
Q1)how to open a like in new tab?
A)using traget property 
ex:
`<a href="http://google.jo" target="_blank">`
-also you can add like to section of the pages using  `href` to a class or an id

# Html Layout 
css treats each element as an block or inline or inline block element.
Q2)whats the deffrence between block box and inline box 
`block`:start a new line and act as the main building block
`inline`:flows within the serounding txt and you can set height and width for the box
>if a block element inside another block element  then the outer box is the parent for both 2 boxes.
### Position
`normal-flow`:Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one
`relative`:is positioned relative to its normal position
`absolute`:is positioned relative to the nearest positioned ancestor
#functions methods and objects
-functions allow you to group a set of related statment togather that represent a single task
-object: is a blue print  variables as property andfunctions as method 
-javascript has several built in objects such as string numbers and math 
-array and objects can be used to craete a complex daata.
ex:to define an object we have 2 ways
1-
var alaa=
{
    name:'alaa',
    age:22,
    birthyear:1997,
    location:amman
},
//object crate
var alaaproto=
{
calcaluteage:function()
{
    console.log(2020-this.yearofbirth);
}
}
var alaa=Object.create(alaaproto);
alaa.name='alaa';
alaa.yearofbirth=1997;
alaa.job='programmer';

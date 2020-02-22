# object
in onjects we have 2 types 
1.premitive:
-Numbers
-strings
-boolean
-undefined
-null
2. every thing else
-arrays
-functions
-objects
-dates
what is an object??
**object**:is a blueprint that allow us to store data and keeping code clean 
>object intract with one another through properties and methods
note:every javascript object has prototype property which makes inheritance possible.
>prototype property is where we put methods and proprties in other object to inherit
>constructer property is in all prototype instancses that are created4
>this is used to indicate the property that belongs to the object
we can create objects in diffrent ways
ex1:
var alaa=
{
    name:alaa,
    age:25,
    birthyear:1997
},
ex2 
var person=function(name,age,birthname)
{
    this.name=name;
    this.age=age;
    this.birthname=birthname;

}
var alaa=new person("alaa",23,1997);
/* DOM :document object model

-its a structed represintion of an html 
-the Dom used to connect web pages to scripts
- in each html box theres an object in the DOM that we can  acssess and  interact with
1 document.getElementById // it will get the value of the element that have an id
2. document.getElementsByTagName // it will get the value of the tag name it will return an object so u have to spisfy the index of object
3.document.getElementsByClassName // get element by its class
4. document.querySelectorAll // to choose any element in html document
5.document.title
6. document.images
7. document.forms
8. value to get the value of an element
9. type to get the type of an element
10. document.body //all the elements inside the body
11.document.anchors //href attribute
12 document.links //links tags
inner text//not standard  
outer text//not standard

inner html// recommended it will return with html tags
outer html//recommnded
text content  //recommended just the text
to set attribute to an element you use element.attribute
examples:
element.id="alaa"
element.class="asdasd"
element.src="link of image"
element.title="alaa"
get attribute set attribute\
example:
element.getattribute("src");
element.setattrubute("alt",'alaa'); or elment.attr()
13. has attribute 
14. remove attribute
15.class list-contatins or length
16 class list-item to select which the index of the class
note1:to acssess a form element u spesify what form you want to select and sleect the element by the name of th e elment then get its value
var getdivid=document.getElementById("intro1").innerHTML='changed by javascript';
var getbytag=document.getElementsByTagName("p");
    getbytag[0].innerHTML="changed by javascript";

var getclass=document.getElementsByClassName("test");
getclass[0].innerHTML='changed by class';
var getqueryselector=document.querySelectorAll(".test");
getqueryselector[1].innerHTML="changed by query selector";
var title=document.getElementById("website-title");
title.innerHTML=document.body.innerText; for(var i=0;i<=document.images.length;i++) { document.write(document.images[i].src+"<br>"); }

example 
if(document.body.innerText.indexOf('almasridsf') > -1)
{
console.log("the string is exist");
}
else
{
    console.log("the string does not exist");
}
var href=document.getElementById("anchors");
href.innerText=document.anchors.length;

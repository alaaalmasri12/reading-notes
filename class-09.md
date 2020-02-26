# Forms
html Forms:HTML forms give you a set of elements to collect data from your users
best example on form is where u send your information for a feedback or registeration or anything that require to send data
![form image](https://uicookies.com/wp-content/uploads/2019/11/Search-Form-v10.jpg)
-theres many way to gather data
1. ADDING Text:single-line-text,password,text area
2. making-Choces:Radio ,checkboxes,drop-down-boxes
3. submiting Forms:submit button,image button,upload button
## how the form works??
>A user fills in a form and then presses a button to submit the information to the server it takes the value based on name attribute for the input
## the form strcture
*form strcture*
`<form>`:This element should always carry the action attribute and will usually have a method.
>in form we have 2 attributes 
1.action:that will take us to another url
2.method:post or get 
example on input
`text`:<input type="text" placehoder="please enter your name">
>you can control the size,width,maxlength for the input
example on radio button:
`radio`:<input type="radio" value="male">male
>you can control the name and checked and value attribute
example on dropdown:
<select>
<option value="jordan">jordan</option>
<option value="egypt">egypt</option>
<option value="lebanon">lebanon</option>
<option value="united states">united state</option>
</select>
example on FIlE Input boX
<input type="file">
# Events
events can trigred by something you do in the page by clicking or hovering on an item
there are multiple events that happends in the page
1. scroll:the user has scrolled down or up
2.keydown:User first presses a key
3.keyup:User releases a key 
4.click:User presses and releases a button over the same element 
5-dblclcik:the same thing as click but when clicked twice
6-mouseover:User moves the mouse over an element
** focus events**
1.focus / focusin :Element gains focus 
2.blur / focusout:Element loses focus 
3.change :Value in select box, checkbox, or radio button changes
Event handlers let you indicate which event you are waiting for on any particular element. There are three types of event handlers. 
1. HTML EVENT HANDLERS :<a onclick="hide()"> bad practice
2. Traditional Dom event handler:They are considered better than HTML event handlers because they let you separate the JavaScript from the HTML. 
3.DOM Level 2 event lsiteners:The syntax is quite different and, unlike traditional event handlers, these newer event listeners allow one event to trigger multiple function

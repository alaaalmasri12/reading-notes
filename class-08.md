# Html layout
**Building Blocks**
>CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box
-we have 2 types of block elements
1. Block-level elements start on a new line 
Examples include:
 `<h1>` 
 `<p> `
` <ul>`
 `<li>`
 2-inline elements flow in Between surrounding text Examples include:
  `<img>` 
  `<b>`
  `<i>`
>if one block level elment sits inside another block element its clalled the contaning orp parent element
>To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed
-We have 5 types of positioning
1.normal flow: Every block-level element appears on a new line causing each item to appear lower down the page than the previous one
2.relative positining:this moves the element from position to it would be in its normal flow
3.absolute Positioning This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.
4.fixed Positioning: This is a form of absolute positioning that positions the element in relation to the browser window
5.floating element:allow you to take the element of its normal flow and position it in a normal flow
example on position realtive:
container.example1 
{ position: relative;
 top: 50px; 
 left: 100px;
}
example on position absoloute
.overlay 
{ position: absolute;
 top: 0px;
  left: 500px;
  background-color:linear-greadient(#000512,#051256);
   width: 250px;
}
example on position:fixed
h1 { 
    position: fixed;
     top: 0px;
    left: 50px; 
     padding: 10px
     margin: 0px;
     width: 100%;
     background-color: #efefef;
     } 
## z-index 
z-index:If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front
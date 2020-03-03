# CSS Transforms, Transitions, and Animations
## Transform
 transform property comes in two different settings two-dimensional and three-dimensional and each of them comes with thier own invidual properties  and values
 Transform Syntax
 the transform property then fellowed by a value
 ex:
 `transform:scale(1.5);`
 ## 2D Transforms:
 Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes otherwise the there-dimensional transform works on both x and y 
 ### 2D Rotate
  The rotate value provides the ability to rotate an element from 0 to 360 degrees Using a positive value will rotate an element clockwise and using negative value it will rotate the element counter clockwise
  ex:
  ### 2D Scale
  using scale will allow you to change the size of of an element the scale will take 2 coridantes x for the width and y for the height.
  ### 2d Translate
  its like a relative positioning that will push and pull element in diffrent diriction the normal flow  
 ### 2D Skew
  is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values
 ### Transform Origin
  To change this default origin position the transform-origin property may be used.
### Perspective
 The perspective for each element can be thought of as a vanishing point, similar to that which can be seen in three-dimensional drawings
 ### 3D Rotate

### Backface Visibility
elements will occasionally be transformed in a way that causes them to face away from the screen. This may be caused by setting the rotateY(180deg) value

# Transitions
element must have a change in state, and different styles must be identified for each state
theres a few properties for tranisition?
1.transition-property 
2.transition-duration 
3.transition-timing-function 
4.transition-delay
## Animations Keyframes
To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated
`Animation Name`:Once the keyframes for an animation have been declared they need to be assigned to an element. To do so, the animation-name property is used with the animation name, identified from the @keyframes rule
`Animation Duration, Timing Function, & Delay`: They include a duration, timing function, and delay if desired. To start, animations need a duration declared using the animation-duration property
`animation-iteration-count`:To have an animation repeat itself numerous times.
`animation-direction` property include normal reverse alternate and alternate-reverse.


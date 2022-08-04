# Flexbox is a set of related CSS properties for building 1-dimensional layouts.

 - The main idea behind flexbox is that empty space inside a container element can be automatically divided by its child elements.

 - Flexbox makes it easy to automatically align items to one another inside a parent container, both horizontally and vertically.

 - Flexbox solves common problems such as vertical centering and creating equal-height columns

 - Flexbox is perfect for replacing floats, allowing us to write fewer and cleaner HTML and CSS code.

 #  Flexbox terminology

 - All we have to do in order to create a flex container is to set its display property to flex.
 **display: flex;**

 - If we do this then all the direct children of that flex container will become the so called flex items.
 - We can use different properties on the flex container and on the flex items.
 - The directions in which these flex items are layed out is called the main axis then the other perpendicular  axis is simply called the cross axis and it's important to know about these names because we can actually change the directions of the main axis and so therefore also of the cross axis plus we can align elements along the main axis and along the cross axis in different ways and therefore we always need to know which axis we are dealing with.

 # CSS properties that are part of the flexbox specification both of the flexbox container and the flexbos items:
 ##  For the flex container the most important ones are:
  ```
   - gap: 0 | <length>
   - justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly
   - align-items: strecth | flex-start | flex-end | center | baseline
   - flex-direction: row | row-reverse | column | column-reverse
   - flex-wrap: nowrap | wrap | wrap-reverse
   - align-content: stretch | flexstart | flex-end | center | space-between | space-around
 ```

 ## For the flex items the most important ones are:
```
- align-self: auto | stretch | flex-start | flex-end | center | baseline
- flex-grow: 0 | <integer>
- flex-shrink: 1 | <integer>
- flex-basis: auto | <length>
- flex: 0 1 auto | <int> <int> <len>
- order: 0 | <integer>
```
 




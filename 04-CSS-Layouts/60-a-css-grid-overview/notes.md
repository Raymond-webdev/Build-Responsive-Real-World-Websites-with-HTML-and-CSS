## What is CSS grid?
- CSS Grid is a se t of CSS properties for building 2-dimenstional layouts.
-  The main idea behind CSS Grid is that we ivide a container element into rows and columns that can be filled with its child elements.
- In two-dimensional contexts, CSS Grid allows us to write less nested HTML and easier to read CSS.
- CSS Grid is not meant to replace flexbox! Instead, they work perfectly together. Need a 1D layout? Use flexbox. Need a 2D layout> Use CSS Grid.

## Basic CSS Grid terminology:
### As we learned in previous lessons, The Grid Container is basically where everything happens and we create a Grid Container by setting its display property to grid.
- display: grid;
### Then all the child elements of the Grid Container wil be the Grid items.
### This is quite similar to flexbox.
### Then also like flexbox we also have axis here so we have a row axis and a column axis.
### Now unlike flexbox we cannot change the directions of the row and the columns axis which in my opinion actually make it even a bit easier to work with CSS Grid.

## More terminology:
### The concept of Grid Lines are those lines which basicaly divide up the grid and separate the columns and the rows.
### These Grid lines are numbered from 1 to the number of columns +1 and the number of rows +1.
### So if we have 3 columns then we have 4 Grid lines for the columns and if we have 2 rows then we have three Grid Lines for the rows.
### These numbers are actually important as we can place a grid item exactly in one place in the grid where we wanted to be.
### The intersection of all these grid lines so both the grid lines for the columns and the rows creates all these areas where we can place all the items and these areas are called the Grid Cells.
### We can also create spaces between the Grid Items and these are called Gutters(gaps)
### One other property the is being used is the Grid Track.

## Properties for Grid Container:
```
- grid-template-rows
- grid-template-columns

 **To establish the grid row and column tracks. One length unit for each track. ANy unit can be used, new fr fills unused space.** 
```
```
- row-gap: 0 | <length> 
- column-gap: 0 | <length>
- gap: 0 | <length>
**To create empty spaces between tracks**
```
```
- justify-content: stretch | start | center | end
- align-items: stretch | start | center | end
**To align items inside rows/columns (horizontally/ vertically)**
```

## Properties for Grid Items:
```
- grid-column: <start line> / <end line> | span <number>
- grid-row: <start line> /<end line> | span <number>
**To place a grid item into a specific cell, based on line numbers.
span keyword can be used to span an item across more cells.**
```
```
- justify-self: stretch | start | center | end
- align-self: stretch | start | center | end
**To overwrite justify-items/ align items for single items.**
```
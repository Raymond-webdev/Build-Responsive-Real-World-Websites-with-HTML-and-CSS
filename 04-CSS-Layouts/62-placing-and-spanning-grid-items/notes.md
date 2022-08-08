### Sometimes it's important to manually place elements in a grid cells other than the predefined one.
### In order to place a grid item into a different grid cell we need to apply the property "grid-column" and "grid-row" to the element in question.

### Example:
```
.example {
    grid-column: 2 / 3; - which means that the item should start at column number 2 and end at column number 3. 
    grid-row: 1 / 2; - which means that the item should start at row number 1 and end at row number 2.
}
```
### Example of spanning a grid item across cells:
 ```
 .example {
     grid-column: 1 / span 3; - this means that the grid item starts at 1 and it spans across 3 cells.
     grid-row: 1 / span 3;
 }
 ```
 ### If we don't know how many cells are in that columns and rows and we want to span the grid item accross all celss then we use the -1 value.
 ### Example:
 ```
 .example {
     grid-column: 1 / -1; -  this spans across all cells 
     grid-row: 1 / -1;
 }
```
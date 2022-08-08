### In this lecture in order to sizing Grid columns and rows, the fr(fraction) unit is used instead of the pixels which makes the page way more flexible.
### Also the column-gap and the row-gap is used in order to create the space between the columns and rows.
### The spae between rows and columns is also called "gutter".

### Example:
```
.container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 150px 150px;
  column-gap: 30px;
  row-gap: 40px;
}
```
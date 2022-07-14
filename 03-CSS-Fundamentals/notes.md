# CSS Fundamentals notes

## Inline, internal and External CSS

**An inline** CSS is used to apply a unique style to a single HTML element.

`Example`

`<h1 style="color:blue;">A Blue Heading</h1>`

**Internal** - by using a <style> element in the <head> section.

`Example`

`<!DOCTYPE html>`

`<html>`

`<head>`

`<style>`

`body {background-color: powderblue;}`

`p    {color: red;}`

`</style>`

`</head>`

`<body>`

`<p>This is a paragraph.</p>`

`</body>`
`</html>`

**External** - by using a <link> element to link to an external CSS file.

`Example`

`<!DOCTYPE html>`

`<html>`

`<head>`

  `<link rel="stylesheet" href="styles.css">`

`</head>`

`<body>`

`<h1>This is a heading</h1>`

`<p>This is a paragraph.</p>`

`</body>`

`</html>`

## Combining selectors

You can create a list of selectors in order to select multiple elements then you can apply the style needed for all of them instead of just going to each individual selector.

**Example**

&rarr;	h1, h2, h3, h4, p, li {
`font-family: sans-serif;`
`color: #444;`
`}`





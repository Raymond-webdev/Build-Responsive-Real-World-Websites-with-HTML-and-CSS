### In this lecture I am going to add a couple of dynamic effects to my page so thing like making the mobile navigation work and also some scrolling animations by using JavaScript. 
### So as a short introduction, JavaScript is basically the programming language of the web.

### In order for the script to apply to our page, I need to connect it to the HTML file by using the script tag withing the head tag.
``` 
<head>
  <title></title>
  <script src="js/script.js"></script>
</head>
```
### Within the script page, I have written the console.log("Hello world") command then went back to the browser and inside the console tab I have check if the "Hello world" outcome is there which confirms that may js page is connected to my HTML page.

### Another very short introduction of JavaScript is by defining variables and then use them.
### Example of a variable:
```
const myName = "Relu Costan";
```
### Also I can select elements from my HTML page just like I can select them in CSS.
### So to do that I write:
```
const h1 = document.queryselector(".heading-primary");

Then I can log it to the console by using the command console.log(h1);
```
### I can either manipulate the HTML tags or the CSS selectors using JavaScript.
### For example I can change the h1 name on my HTML page by using the command below which is going to change the title with my name:

```
h1.textcontent = myName;
```

### Also CSS can be manipulated using javaScript just like the example below:
```
h1.style.backgroundColor = "red";
h1.style.padding = "5rem";
```


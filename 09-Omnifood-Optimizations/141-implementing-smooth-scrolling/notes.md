### In this lecture I am going to use JavaScript to  implement the smooth scrolling.

### Firstly we need to implement the scrolling inside the HTML page

- So on one of the buttons, when we click it I wanted to move to the call to action section so in order for this to happen I need to add an id="cta" to the call to action section in order to give this element a unique name.
- Then on that particular button inside its href attribute, we can add the cta id in order to create the page anchor.
- So when I now click on that button, it will take me to that particular section of the page.
- We can do this trick on all our sections and all our links.

### Example:
``` <a href="#cta" class="btn btn--full margin-right-sm"
    >Start eating well</a
```        

### One other way to implement the smooth scrolling is to add the "scroll-behavior: smooth" inside the "html" property but bear in mind this does not work on Safari browser.

### Example:
```
html {
    scroll-behavior: smooth;
}
```

### Another way to implement smooth scrolling is to use JavaScript by creating a variable which selects all the a:links on the page.

```
const allLinks = document.querySelectorAll("a:link");

allLinks.forEach(function(link){
    link.addEventListener ("click", function(e) {
      e.preventDefault();  
      const href =  link.getAttribute("href");
      console.log(href);

// In order to scroll to the top we need to apply the following function:

      if (href === "#")
   windows.scrollTo({
       top: 0,
       behavior: "smooth",
      })

      if (href !== "#" && href.startsWith("#"))
      const sectionEl = document.querySelector(href);
      sectionEl.scrollIntoView({ behavior: "smooth" })
      }
    })
})
```





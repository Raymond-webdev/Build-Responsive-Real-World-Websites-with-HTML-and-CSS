### In this lecture I am going to implement a sticky navigation bar.

1. THe first step is to create a new class which I will then style to make the navigation sticky.
- I am going to create a class called .sticky with a position absolute.
- This class is going to be added to the header 

### Example:
```
.sticky {
    position: fixed;
    top: 0;
    bottom: 0;
    width: 100%;
    height: 8rem;
    padding-top: 0;
    padding-bottom: 0;
    background-color: rgba(255, 255, 255, 0.97);
    z-index: 999;
    box-shadow: 0 1.2rem 3.2rem rgba(0, 0, 0, 0.03);
}
```

### In our project we want the sticky navigations to appear as soon as the hero section is no longer visible so we can use JavaScript to do exactly that.

### the way we can do this is by using a very modern way which is called the IntersectionObserver.

```
const sectionHeroEl = document.querySelector(".section-hero");

const obs =  new IntersectionObserver (function(entries){
  const ent = entries[0];
  console.log(ent);

  if(ent.isIntersecting === false){
  document.body.classList.add("sticky");
  }
}, 
{
    root: null,
    threshold: 0;
});
observer.observe(sectionHeroEl)
```
### In order to remove the sticky navigation as soon as we scroll back up to the top we need to add the following javaScript code:
```
if(ent.isIntersecting === true){
  document.body.classList.remove("sticky");
  }
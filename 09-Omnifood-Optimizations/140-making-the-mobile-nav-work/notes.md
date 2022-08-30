### In this lecture I am going to make the mobile navigation work.

1. The first step I have created a class called "nav-open" which is going to be placed automatically inside the header whenever the three lines button at the top right of the page is clicked and also it's going to be removed whenever we exit the three line button with the help of JavaScript.


 2. In order for this certain action to happen we need to click on the button with the class of "btn-mobile-nav".

 3. A variable needs to be created below:

 const btnNavEl = document.queryselector(".btn-mobile-nav);

 4. The second variable the I need to create and it's relevant to our code is the "header" variable:

 const headerEl = document.queryselector(".header);

 5. We are going to add the eventListener now which is going to create the relevant action by clicking on the button and in our what "toggle" function will do , is to look at the element "headerEl" and if it does have the "nav-open" class, it will then not add it and if it's not there then it will add it.


 btnNavEL.addEventListener("click", function(){
     headerEl.classList.toggle("nav-open");
 })

### I have chosen the **Rubik" type face in order to make the text look more rounded and more welcoming.

body {
    font-family: "Rubik", sans-serif;
}

### I have also built another component for the hero section which is to have some customer photos with some relevant data.
```
 <div class="delivered-meals">
                <div class="delivered-imgs">
                    <img src="img/customers/customer-1.jpg"
                    alt="Customer photo"/>
                   <img src="img/customers/customer-2.jpg"
                    alt="Customer photo"/>
                   <img src="img/customers/customer-3.jpg"
                    alt="Customer photo"/>
                   <img src="img/customers/customer-4.jpg"
                    alt="Customer photo"/>
                   <img src="img/customers/customer-5.jpg"
                    alt="Customer photo"/>
                   <img src="img/customers/customer-6.jpg"
                    alt="Customer photo"/>
                </div>
                <p class="delivered-text">
                    250,000+ meals  delivered last year!
                </p>
            </div>

```
### In order to make the images sit side by side, I have used the flex property and also I have used a negative margin-right in order to make the images overlap.

```
.delivered-imgs img{
        display: flex;
        height: 4.8rem;
        width: 4.8rem;
        border-radius: 50%;
        margin-right: -1.6rem;
    }

```
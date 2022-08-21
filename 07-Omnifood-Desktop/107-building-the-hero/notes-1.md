### In this lecture I have managed to create the hero section where I have the hero image on the right side and then the content and some description on the left side.
```
<body>
    <section class="section-hero">
        <div class="hero">
         <div class="hero-text-box">
            <h1 class="heading-primary">
                A healthy meal delivered to your door, every single day
            </h1>
            <p class="hero-description">
                The smart 365-days-per-year food subscription that will make you eat healthy again. 
                Tailored to your personal tastes and nutritional needs. We have delivered 250,000+ meals last year!
            </p>
            <a href="#" class="btn btn--full margin-right-sm">Start eating well</a>
            <a href="#" class="btn btn--outline">Learn more &darr;</a>
         </div>
         <div class="hero-image-box">
             <img src="img/hero.png" 
                class="hero-img" 
                alt="woman enjoying food, meals in storage container and food bowls on a table"/>
         </div>
        </div>
    </section>
   </body>
   ```

   ```
   body {
    font-family: sans-serif;
    line-height: 1;
    font-weight: 400;
    color: #555;
}

.section-hero {
    background-color: #fdf2e9;  
    padding: 9.6rem 0;  
}

.hero {
    max-width: 130rem;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 9.6rem;
    align-items: center;
    
}

.heading-primary {
  font-size: 5.2rem;
  font-weight: 700;
  line-height: 1.05;
  color: #333;
  letter-spacing: -0.5px;
  margin-bottom: 3.2rem;
}

.hero-description {
    font-size: 2rem;
    line-height: 1.6;
    margin-bottom: 4.8rem;
}

.btn:link,
.btn:visited {
    display: inline-block;
      background-color: #e67e22;
      font-size: 2rem;
      text-decoration: none;
      padding: 1.6rem 3.2rem;
      border-radius: 0.9rem;

      /* The transition property is a propery that allows us to transition between two values using an animation */
      transition: all 0.3s;     
}

.btn--full:link, .btn--full:visited {
    background-color: #e67e22;
    color: #fff;
    margin-right: 1.6rem;
}


.btn--full:hover, .btn--full:active {
    background-color: #cf711f;
    color: #fff;
}

.btn--outline:link, .btn--outline:visited {
      background-color: #fff;
      color: #555;
}

.btn--outline:hover, .btn--outline:active {
    background-color: #fdf2e9;
    /* border: 3px solid #fff; */

    /* Trick to add border inside the button */
    box-shadow: inset 0 0 0 3px #fff;
}

.hero-img {
    width: 100%;
}

.margin-right-sm {
    margin-right: 1.6rem !important;
}
```
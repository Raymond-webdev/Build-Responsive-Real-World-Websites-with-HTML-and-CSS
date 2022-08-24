### In this section I am going to use the @ media query of a max-width of 944px.

### Example:
```
/**************************************/
/* BELOW 944px (Tablets) */
/**************************************/

@media(max-width: 59em) {
  html {
      font-size: 50%;
  }

  .hero {
      grid-template-columns: 1fr;
      padding: 0 8rem;
      gap: 6.4rem;
  }

   .hero-text-box, .hero-img-box {
       text-align: center;
   }

  .hero-img {
      width: 60%;
  }

  .delivered-meals {
      justify-content: center;
      margin-top: 3.2rem;
  }

  .logos img {
      height: 2.4rem;
  }
  .step-number {
      font-size: 7.4rem;
  }

  .meal-content {
      padding: 2.4rem 3.2rem 3.2rem 3.2rem;
  }

  .section-testimonials {
      grid-template-columns: 1fr;
  }

  .gallery {
      grid-template-columns: repeat(6, 1fr);
    }

      .cta {
          grid-template-columns: 3fr 2fr;
      }

      .cta-form{ 
          grid-template-columns: 1fr;;
      }

      .btn--form {
          margin-top: 1.2rem;
      }
  }
```

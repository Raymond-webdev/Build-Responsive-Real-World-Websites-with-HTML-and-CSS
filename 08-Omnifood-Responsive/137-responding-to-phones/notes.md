### Responding to phones

#### Example:
```
/**************************/
  /* BELOW 544px (Phones) */
  /**************************/
  
  @media (max-width: 34em) {
    .grid {
      row-gap: 4.8rem;
    }
  
    .grid--2-cols,
    .grid--3-cols,
    .grid--4-cols {
      grid-template-columns: 1fr;
    }
  
    .btn,
    .btn:link,
    .btn:visited {
      padding: 2.4rem 1.6rem;
    }
  
    .section-hero {
      padding: 2.4rem 0 6.4rem 0;
    }
  
    .hero {
      padding: 0 3.2rem;
    }
  
    .hero-img {
      width: 80%;
    }
  
    .logos img {
      height: 1.2rem;
    }
  
    .step-img-box:nth-child(2) {
      grid-row: 1;
    }
  
    .step-img-box:nth-child(6) {
      grid-row: 5;
    }
  
    .step-img-box {
      transform: translateY(2.4rem);
    }
  
    .testimonials {
      grid-template-columns: 1fr;
    }
  
    .gallery {
      grid-template-columns: repeat(4, 1fr);
      gap: 1.2rem;
    }
  
    .cta {
      grid-template-columns: 1fr;
    }
  
    .cta-text-box {
      padding: 3.2rem;
    }
  
    .cta-img-box {
      height: 32rem;
      grid-row: 1;
    }
  }
  ```
### Responding to smaller tablets 

### Example:

```
/**************************************/
/* BELOW 944px ( Smaller tablets) */
/**************************************/
@media(max-width: 44em) {
   .grid--3-cols,
   .grid--4-cols {
       grid-template-columns: repeat(2, 1fr);
   }

   .diets {
       grid-column: 1 / -1;
       justify-self: center;
   }

   .heading-secondary {
       margin-bottom: 4.8rem;
   }

   .pricing-plan {
       width: 100%;
   }

   .gird-footer {
       grid-template-columns: repeat(6, 1fr);
   }

.logo-col, .address-col {
    grid-column: span 3;
}

   .nav-col {
       grid-row: 1;
       grid-column: span 2;
       margin-bottom: 3.2rem;
       }
}
```
### In this lecture I am starting targeting mobile devices and in particular we will make the website responde to landscape tablets.

###Example:
```
/**************************************/
/* BELOW 1200px (Landscape Tablets) */
/**************************************/

@media(max-width: 75em) {
    html {
        font-size: 56.25%;
    }

    .grid {
       column-gap: 4.8rem;
       row-gap: 6.4rem;
    }

    .heading-secondary {
        font-size: 3.6rem;
    }

    .heading-tertiary {
        font-size: 2.4rem;
    }
}
```
### Below there is just an example of where the website design would change by applying the @media peoperty of max-width: 84em(1344px) for smaller desktops.

```
/**************************************/
/* BELOW 1344px (Smaller desktops) */
/**************************************/

@media(max-width: 84em) {
    .hero {
        max-width: 120rem;
    }

    .heading-primary {
    font-size : 4.4rem;
    }

    .gallery {
    grid-template-columns: repeat(2, 1fr);
    }
}
```
### max-width 

- The max-width CSS property sets the maximum width of an element. It prevents the used value of the width property from becoming larger than the value specified by max-width


.test {
    /* width: 1000px; */
    background-color: red;
    padding: 100px;
    max-width: 1000px;
}

## rem unit

- Rem stands for the "root elements font-size".
```
.test {
    /* width: 1000px; */
    background-color: red;
    
    /* max-width: 1000px; */

    max-width: 50rem;
    padding: 4rem;
    color: #fff;
    font-size: 2rem;
    /* 1rem = 16px */
}
```
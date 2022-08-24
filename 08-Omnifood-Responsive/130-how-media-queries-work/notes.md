### How media queries work (with max-width)

 The @media rule is used in media queries to apply different styles for different media types/devices.

Media queries can be used to check many things, such as:

- width and height of the viewport
- width and height of the device
- orientation (is the tablet/phone in landscape or portrait mode?)
- resolution

### Examples:
```
@media (max-width: 1200px) {
  .section-hero {
    background-color: orangered;
  }
}

@media(max-width: 600px){
  .section-hero {
    border: 20px dashed blue;
    /* background-color: blue; */
  }
}
```
### In this lecture I am going to give some examples that will help me to optimize the website's images.

1. One way to optimise the images is to resize them by adjusting the intrinsic size to be double of the rendered size.
Also you will need a program in order to resize the images where it can be found on google.

2. Another way to optimise an image is to compress it in order to reduce the file size.
A special tool that we can use to compress images is Squoosh from squoosh.app or you can just drop the image on the website and compress it.

3. In order to make sure our resized images are available on most browsers, we can use the ```<picture></picture>``` element where the browser can choose the right image in order to display it.
```
<picture>
   <source srcset ="img/hero.webp" 
   type ="image/webp" />
   <source srcset = "img/hero-min.png"
   type = "image/png" />

   <img 
     src = "img/hero.webp"
     alt = "woman enjoying food" />
</picture>
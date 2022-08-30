### In this lecture I am going to add the favicon and the meta description.

### Meta description is basically a short summary of our webstie's content and it's also the texts that will appear for each of the search results in google and other search engines.
### To add that to our page, we once again use the meta element.

```
 <meta charset="UTF-8" />
 <meta http-equiv="X-UA-Compatible" content="IE=edge" />
 <meta
    name="description"
    content="Omnifood is an AI-powered food subscription that will make you eat healthy again, 365 days per year. It's tailored to your personal tastes and nutritional needs."
 />
```

### Also we need to add the favicon item in order to change the image displayed next to the title in the browser tab.
### To includ the fav icon, we actually also use the link element.
```
<link rel="icon" href="img/favicon.png" />
```

### Also in order to created a favicon icon for apple android users, we need to add the below:

### Apple devices
```
<link rel="apple-touch-icon" href="img/apple-touch-icon.png" />
```

### Android devices:
```
<link rel="manifest" href="manifest.webmanifest" />
```

### In this last lecture I am going to use the Netlify forms feature in order to make our sing up form work.

### So in the menu of our site we have the "form" tab where we can manage forms and submissions without any server-side code or JavaScript.

### All we need to do is to add a name to our form by adding the netlify attribute. And ofcourse this will only work if you deploy your site using Netlify.
### Example:
```
<form class="cta-form" name="sign-up" netlify>
```

### In order to make this work, we also need to add a "name" attribute to the other fields.

### Example:
```
<div>
    <label for="full-name">Full Name</label>
    <input
      id="full-name"
      type="text"
      placeholder="John Smith"
      name="full-name"
      required
    />
</div>

<div>
   <label for="email">Email address</label>
   <input
     id="email"
     type="email"
     placeholder="me@example.com"
     name="email"
     required
   />
</div>
```

### Then we go back to our Netlify menu and click on "Deploys" and we have again our area where we can just drop our folder.
### So now if we go back to our website and fill out our form with the relevant info, the form will be processesd and we will get a "Thank you! Your form submission has been received" message.
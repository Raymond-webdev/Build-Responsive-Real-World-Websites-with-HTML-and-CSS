## What is **Responsive Design?**

 - ### Design technique to make a webpage adjust its layout and visual style to **any possible screen size** (window or viewport size).
 - ### In practice, this means that responsive design makes websites usable on all devices, such as **desktop computers, tablets, and mobile phones.**
 - ### It's a set of practices, **not a separate technology.** It's all just CSS! 

 ## Responsive design **Ingredients**

 1. FLUID LAYOUTS

 - To allow the webpage to adapt to the **current viewport** width (or even height)
 - Use % (or vh / vw) unit instead of px for elements that **should adapt to viewport(usually layout)**
 - Use max-width instead of width 


 2. RESPONSIVE UNITS

- Use rem unit instead of px for most lenghts
- To make it easy to **scale the entire layout down** (or up) automatically
- **Helpfull trick:** setting 1rem to 10px for easy calculations

 3. FLEXIBLE IMAGES 

 - By default, images **don't scale automatically** as we change the viewport, so we need to fix that
 - Always use % for image dimenstions, together with the max-width property


 4. MEDIA QUERIES

 - Bring responsive sites to life!
 - To change CSS styles on **certain viewport widths** (called breakpoints)


 ## Desktop-First **VS.** Mobile-First Development

 ### Desktop-First

 - Start writing CSS for the desktop: **large screen**
 - Then, media queries **shrink design** to smaller screens.

 ### Mobile-First

 - Start writing CSS for mobile devices: **small screens**
 - Then, media queries **expand design** to a large screen
 - Forces us to reduce websites and apps to the **absolute essentials**

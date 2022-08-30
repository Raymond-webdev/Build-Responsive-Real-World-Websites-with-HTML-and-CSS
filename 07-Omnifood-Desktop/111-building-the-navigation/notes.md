### In this lecture I am building the navigation for the Omnifood webpage

### Below is the html navigation example where wi have created the nav component which includes the unordered list.
```
<header class="header">
      <a href="#">
        <img class="logo" alt="Omnifood logo" src="img/omnifood-logo.png" />
      </a>

      <nav class="main-nav">
        <ul class="main-nav-list">
          <li><a class="main-nav-link" href="#how">How it works</a></li>
          <li><a class="main-nav-link" href="#meals">Meals</a></li>
          <li>
            <a class="main-nav-link" href="#testimonials">Testimonials</a>
          </li>
          <li><a class="main-nav-link" href="#pricing">Pricing</a></li>
          <li><a class="main-nav-link nav-cta" href="#cta">Try for free</a></li>
        </ul>
      </nav>
      ```

      ### CSS example: I have used the flexbox component Alongside the hover property.
      Also I have used the CSS transition in order to change the property value, over a iven duration.

  

/**************************/
/* NAVIGATION */
/**************************/

.main-nav-list {
  list-style: none;
  display: flex;
  align-items: center;
  gap: 4.8rem;
}

.main-nav-link:link,
.main-nav-link:visited {
  display: inline-block;
  text-decoration: none;
  color: #333;
  font-weight: 500;
  font-size: 1.8rem;
  transition: all 0.3s;
}

.main-nav-link:hover,
.main-nav-link:active {
  color: #cf711f;
}

.main-nav-link.nav-cta:link,
.main-nav-link.nav-cta:visited {
  padding: 1.2rem 2.4rem;
  border-radius: 9px;
  color: #fff;
  background-color: #e67e22;
}

.main-nav-link.nav-cta:hover,
.main-nav-link.nav-cta:active {
  background-color: #cf711f;
}
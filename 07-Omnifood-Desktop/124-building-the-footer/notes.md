### In this lecture I am building the "Footer" section where in the first column I have the logo then some social links and the copyright notiec.
### In the second column I will have some contact information of the Omnifood company.
### In the remaining three columns there will be some there will be some additional links.

### Below I have the CSS example where I have used the grid property alongside the flexbox property.
### Also within the flex container, I have used the flex-direction property so I can place all the items vertically.

```
.footer {
  padding: 12.8rem 0;
  border-top: 1px solid #eee;
}

.grid--footer {
  grid-template-columns: 1.5fr 1.5fr 1fr 1fr 1fr;
}

.logo-col {
  display: flex;
  flex-direction: column;
}

.footer-logo {
  display: block;
  margin-bottom: 3.2rem;
}

.social-links {
  list-style: none;
  display: flex;
  gap: 2.4rem;
}

.social-icon {
  height: 2.4rem;
  width: 2.4rem;
}

.copyright {
  font-size: 1.4rem;
  line-height: 1.6;
  color: #767676;
  margin-top: auto;
}

.footer-heading {
  font-size: 1.8rem;
  font-weight: 500;
  margin-bottom: 4rem;
}

.contacts {
  font-style: normal;
  font-size: 1.6rem;
  line-height: 1.6;
}

.address {
  margin-bottom: 2.4rem;
}

.footer-nav {
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 2.4rem;
}

.footer-link:link,
.footer-link:visited {
  text-decoration: none;
  font-size: 1.6rem;
  color: #767676;
  transition: all 0.3s;
}

.footer-link:hover,
.footer-link:active {
  color: #555;
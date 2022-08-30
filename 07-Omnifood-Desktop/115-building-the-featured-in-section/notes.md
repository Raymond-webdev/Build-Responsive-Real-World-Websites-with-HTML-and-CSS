### Below there is an example of the Featured-in section:

### Inside the HTML file I have added the images required:
```
  <section class="section-featured">
        <div class="container">
          <h2 class="heading-featured-in">As featured in</h2>
          <div class="logos">
            <img src="img/logos/techcrunch.png" alt="Techcrunch logo" />
            <img
              src="img/logos/business-insider.png"
              alt="Business Insider logo"
            />
            <img
              src="img/logos/the-new-york-times.png"
              alt="The New York Times logo"
            />
            <img src="img/logos/forbes.png" alt="Forbes logo" />
            <img src="img/logos/usa-today.png" alt="USA Today logo" />
          </div>
        </div>
      </section>
      
```
      ### Below is the CSS example where I have used the flexbox property in order to align the items side by side.

      .section-featured {
  padding: 4.8rem 0 3.2rem 0;
}

.heading-featured-in {
  font-size: 1.4rem;
  text-transform: uppercase;
  letter-spacing: 0.75px;
  font-weight: 500;
  text-align: center;
  margin-bottom: 2.4rem;
  color: #888;
}

.logos {
  display: flex;
  justify-content: space-around;
}

.logos img {
  height: 3.2rem;
  filter: brightness(0);
  opacity: 50%;
}
### In this lecture I am going to create the testimonial section.
### In this section I am going to put the customer testimonials and the photo gallery side by side by using the grid property and also used a special property (transform: scale()) in order to zoom out the images.


### HTML example: 
```
 <section class="section-testimonials">
        <div class="testimonials-container">
          <span class="subheading">Testimonials</span>
          <h2 class="heading-secondary">Once you try it, you can't go back</h2>

          <div class="testimonials">
            <figure class="testimonial">
              <img
                class="testimonial-img"
                alt="Photo of customer Dave Bryson"
                src="img/customers/dave.jpg"
              />
              <blockquote class="testimonial-text">
                Inexpensive, healthy and great-tasting meals, without even
                having to order manually! It feels truly magical.
              </blockquote>
              <p class="testimonial-name">&mdash; Dave Bryson</p>
            </figure>

            <figure class="testimonial">
              <img
                class="testimonial-img"
                alt="Photo of customer Ben Hadley"
                src="img/customers/ben.jpg"
              />
              <blockquote class="testimonial-text">
                The AI algorithm is crazy good, it chooses the right meals for
                me every time. It's amazing not to worry about food anymore!
              </blockquote>
              <p class="testimonial-name">&mdash; Ben Hadley</p>
            </figure>

            <figure class="testimonial">
              <img
                class="testimonial-img"
                alt="Photo of customer Steve Miller"
                src="img/customers/steve.jpg"
              />
              <blockquote class="testimonial-text">
                Omnifood is a life saver! I just started a company, so there's
                no time for cooking. I couldn't live without my daily meals now!
              </blockquote>
              <p class="testimonial-name">&mdash; Steve Miller</p>
            </figure>

            <figure class="testimonial">
              <img
                class="testimonial-img"
                alt="Photo of customer Hannah Smith"
                src="img/customers/hannah.jpg"
              />
              <blockquote class="testimonial-text">
                I got Omnifood for the whole family, and it frees up so much
                time! Plus, everything is organic and vegan and without plastic.
              </blockquote>
              <p class="testimonial-name">&mdash; Hannah Smith</p>
            </figure>
          </div>
        </div>

        <div class="gallery">
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-1.jpg"
              alt="Photo of beautifully
            arranged food"
            />
            <!-- <figcaption>Caption</figcaption> -->
          </figure>
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-2.jpg"
              alt="Photo of beautifully
            arranged food"
            />
          </figure>
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-3.jpg"
              alt="Photo of beautifully
            arranged food"
            />
          </figure>
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-4.jpg"
              alt="Photo of beautifully
            arranged food"
            />
          </figure>
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-5.jpg"
              alt="Photo of beautifully
            arranged food"
            />
          </figure>
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-6.jpg"
              alt="Photo of beautifully
            arranged food"
            />
          </figure>
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-7.jpg"
              alt="Photo of beautifully
            arranged food"
            />
          </figure>
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-8.jpg"
              alt="Photo of beautifully
            arranged food"
            />
          </figure>
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-9.jpg"
              alt="Photo of beautifully
            arranged food"
            />
          </figure>
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-10.jpg"
              alt="Photo of beautifully
            arranged food"
            />
          </figure>
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-11.jpg"
              alt="Photo of beautifully
            arranged food"
            />
          </figure>
          <figure class="gallery-item">
            <img
              src="img/gallery/gallery-12.jpg"
              alt="Photo of beautifully
            arranged food"
            />
          </figure>
        </div>
      </section>
      ```
      CSS example:

      /**************************/
/* TESTIMONIALS SECTION */
/**************************/

.section-testimonials {
  background-color: #fdf2e9;
  display: grid;
  grid-template-columns: 55fr 45fr;
  align-items: center;
}

.testimonials-container {
  padding: 9.6rem;
}

.testimonials {
  display: grid;
  grid-template-columns: 1fr 1fr;
  row-gap: 4.8rem;
  column-gap: 8rem;
}

.testimonial-img {
  width: 6.4rem;
  border-radius: 50%;
  margin-bottom: 1.2rem;
}

.testimonial-text {
  font-size: 1.8rem;
  line-height: 1.8;
  margin-bottom: 1.6rem;
}

.testimonial-name {
  font-size: 1.6rem;
  color: #6f6f6f;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.6rem;
  padding: 1.6rem;
}

.gallery-item {
  overflow: hidden;
}

.gallery-item img {
  display: block;
  width: 100%;
  transition: all 0.4s;
}

.gallery-item img:hover {
  transform: scale(1.1);
}
### In this lecture I am building the "Pricing" section by creating the 2 pricing tables with the name of the plan at the top and a list of the features that are included in the pricing plan and finally also a "call to action" plan below.

### HTML example:
```
<section class="section-pricing">
        <div class="container">
          <span class="subheading">Pricing</span>
          <h2 class="heading-secondary">
            Eating well without breaking the bank
          </h2>
        </div>

        <div class="container grid grid--2-cols margin-bottom-md">
          <div class="princing-plan princing-plan--starter">
            <header class="plan-header">
              <p class="plan-name">Starter</p>
              <p class="plan-price"><span>$</span>399</p>
              <p class="plan-text">per month. That's just $13 per meal!</p>
            </header>
            <ul class="list">
              <li class="list-item">
                <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
                <span>1 meal per day</span>
              </li>
              <li class="list-item">
                <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
                <span>Order from 11am to 9pm</span>
              </li>
              <li class="list-item">
                <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
                <span>Delivery is free</span>
              </li>
              <li class="list-item">
                <ion-icon class="list-icon" name="close-outline"></ion-icon>
              </li>
            </ul>
            <div class="plan-sing-up">
              <a href="#" class="btn btn--full">Start eating well</a>
            </div>
          </div>

          <div class="princing-plan princing-plan--complete">
            <header class="plan-header">
              <p class="plan-name">Complete</p>
              <p class="plan-price"><span>$</span>649</p>
              <p class="plan-text">per month. That's just $11 per meal!</p>
            </header>
            <ul class="list">
              <li class="list-item">
                <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
                <span><strong>2 meals</strong> per day</span>
              </li>
              <li class="list-item">
                <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
                <span>Order <strong>24/7</strong></span>
              </li>
              <li class="list-item">
                <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
                <span>Delivery is free</span>
              </li>
              <li class="list-item">
                <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
                <span>Get access to latest recipes</span>
              </li>
            </ul>
            <div class="plan-sing-up">
              <a href="#" class="btn btn--full">Start eating well</a>
            </div>
          </div>
        </div>

        <div class="container grid">
          <aside class="plan-details">
            Prices include all applicable taxes. You can cancel at any time.
            Both plans include the following:
          </aside>
        </div>
 ```

        CSS example:

        .section-pricing {
  padding: 9.6rem 0;
}

.princing-plan {
  border-radius: 11px;

  width: 75%;
}

.princing-plan--starter {
  justify-self: end;
  border: 2px solid #fdf2e9;
  padding: 4.6rem;
}

.princing-plan--complete {
  background-color: #fdf2e9;
  padding: 4.8rem;
  position: relative;
  overflow: hidden;
}

.princing-plan--complete::after {
  content: "Best value";
  position: absolute;
  top: 6%;
  right: -18%;

  text-transform: uppercase;
  font-size: 1.4rem;
  font-weight: 700;
  color: #333;
  background-color: #ffd43b;
  padding: 0.8rem 8rem;
  transform: rotate(45deg);
}

.plan-header {
  text-align: center;
  margin-bottom: 4.8rem;
}

.plan-name {
  color: #cf711f;
  font-weight: 600;
  font-size: 2rem;
  text-transform: uppercase;
  letter-spacing: 0.75;
  margin-bottom: 3.2rem;
}

.plan-price {
  font-size: 6.2rem;
  font-weight: 600;
  color: #333;
  margin-bottom: 1.6rem;
}

.plan-price span {
  font-size: 3rem;
  font-weight: 500;
  margin-right: 0.8rem;
}

.plan-text {
  font-size: 1.6rem;
  line-height: 1.6;
  color: #6f6f6f;
}

.plan-sing-up {
  text-align: center;
  margin-top: 4.8rem;
}

.plan-details {
  font-size: 1.6rem;
  line-height: 1.6;
  text-align: center;
}

.feature-icon {
  color: #e67e22;
  height: 3.2rem;
  width: 3.2rem;
  background-color: #fdf2e9;
  margin-bottom: 3.2rem;
  padding: 1.6rem;
  border-radius: 50%;
}

.feature-title {
  font-size: 2.4rem;
  color: #333;
  font-weight: 700;
  margin-bottom: 1.6rem;
}

.feature-text {
  font-size: 1.8rem;
  line-height: 1.8;
}
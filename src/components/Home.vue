<template>
  <main>
    <section class="hero | bg-clr-primary-300">
      <div class="flex">
        <div class="social | flex items-end">
          <ul class="social__icons | grid gap-4">
            <li>
              <a href="#"
                ><img src="../assets/images/twitter.svg" alt="twitter"
              /></a>
            </li>
            <li>
              <a href="#"
                ><img src="../assets/images/instagram.svg" alt="instagram"
              /></a>
            </li>
            <li>
              <a href="#"
                ><img src="../assets/images/facebook.svg" alt="facebook"
              /></a>
            </li>
            <li>
              <a href="#"
                ><img src="../assets/images/mail.svg" alt="email"
              /></a>
            </li>
          </ul>
        </div>
        <div>
          <div class="hero__model1">
            <h1 class="logo">Brish.</h1>
            <img src="../assets/images/model-1.png" alt="model 1" />
          </div>
        </div>
      </div>
      <article class="hero__right | relative">
        <nav class="primary__nav">
          <ul class="nav__links | flex items-center justify-between fs-300">
            <li><a href="#">Home</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Events</a></li>
            <li><a href="#">Contact Us</a></li>
            <li><button class="button">Book a model</button></li>
          </ul>
        </nav>
        <section class="hero__content | grid gap-6">
          <h1 class="fs-200">MODELLING AGENCY</h1>
          <h2 class="ff-accent fs-800 fw-bold">
            Be Bold. Be Black.
            <br />
            Hire The Best One.
          </h2>
          <p class="hero__text">
            Modeling is the culmination of lighting, texture, body movement, and
            your soul's expression. Brish models don't go with the trend, we set
            the trend.
          </p>
        </section>
        <!-- <img class="model-2" src="../assets/images/model-2.png" alt="">
        <img class="model-3" src="../assets/images/model-3.png" alt=""> -->
      </article>
    </section>

    <section class="about">
      <div class="flow | about__content">
        <h2 class="ff-accent fs-700 fw-bold">About Us</h2>
        <p class="about__text">
          We are leading male modeling agency in Africa with many years of
          experience in commercial print, television commercials, international
          runways and fashion prints. We provide a platform for aspiring models
          to promote themselves, develop and market their talents. We are into
          commercial modeling and actors/talents management.
        </p>
        <div class="flex items-center gap-4 fw-semibold">
          <span class="text-clr-primary-400 fs-300 ">Read more</span>
          <img src="../assets/images/arrow.svg" alt="" />
        </div>
      </div>
      <div>
        <img class="model-4" src="../assets/images/model-4.png" alt="model 4" />
      </div>
    </section>

    <div class="bg-clr-primary-300">
      <section class="events">
        <div>
          <img class="model-5" src="../assets/images/model-5.png" alt="model 5" />
        </div>
        <div>
          <div>
            <h2 class="ff-accent fs-700 fw-bold">Events</h2>
            <p class="events__text">
              Our models deliver innovative, entertaining, trustworthy services for
              brands for fashion events, lifestyles, and also product branding...
            </p>
            <div class="flex items-center gap-4 fw-semibold">
              <span class="text-clr-primary-400 fs-300">View More Events</span>
              <img src="../assets/images/arrow.svg" alt="" />
            </div>
          </div>
          <div class="events__carousel">
          </div>
        </div>
      </section>
    </div>
  </main>
</template>

<script setup></script>

<style scoped>
.hero {
  /* min-height: 100vh; */
  display: grid;
  gap: 1rem;
  /* grid-template-columns: 1fr 1fr; */
  grid-template-columns: 1fr 1.5fr;
  overflow: hidden;
}

.hero__model1 {
  display: grid;
}

.logo {
  font-family: var(--ff-logo);
  font-size: 3.125rem;
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke: 1.2px var(--clr-neutral-100);
  margin: 1.5rem 1rem;
  grid-column: 1 / -1;
  grid-row: 1 / -1;
  z-index: 10;
}

.hero__model1 img {
  height: 100vh;
  grid-column: 1 / -1;
  grid-row: 1 / -1;
}

.social {
  margin: 2rem;
}

.social__icons img {
  min-width: 2.5rem;
}

.primary__nav {
  margin-block-start: 1rem;
  max-width: 44rem;
}

.hero__right {
  max-width: 54rem;
  isolation: isolate;
}

.hero__content {
  margin-top: 3rem;
}

.hero__text {
  max-width: 40ch;
}

.model-2 {
  width: 345px;
  position: absolute;
  z-index: -1;
  bottom: -7rem;
  left: 6rem;
}

.model-3 {
  width: 295px;
  position: absolute;
  z-index: -1;
  right: 0;
  bottom: 6rem;
}

.about {
  display: grid;
  grid-template-columns: 1fr 1fr;
  /* justify-items: end; */
  align-items: center;
}

.about > div:nth-child(2) {
  justify-self: end;
}

.about__content {
  margin-inline-start: 7rem;
}

.about__text {
  max-width: 40ch;
}

.model-4 {
  height: 100vh;
}

.events {
  display: grid;
  gap: 1rem;
  grid-template-columns: 1fr 1.5fr;
  justify-items: center;
  margin-inline-start: 3rem;
}

.model-5 {
  height: 100vh;
}

.events__text {
  max-width: 40ch;
}
</style>

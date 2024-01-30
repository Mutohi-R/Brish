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
                <img src="../assets/images/model-1.png" alt="model 1">
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
        <section class="hero__content | grid gap-4">
          <h1 class="fs-200">MODELLING AGENCY</h1>
          <h2 class="fs-800 fw-bold">
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
        <img class="model-2" src="../assets/images/model-2.png" alt="">
        <img class="model-3" src="../assets/images/model-3.png" alt="">
      </article>
    </section>
  </main>
</template>

<script setup></script>

<style scoped>
.hero {
    height: 100vh;
    display: grid;
    /* grid-auto-flow: column; */
    gap: 1rem;
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
    width: 100%;
    min-width: 400px;
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
    max-width: 44rem;
}

.hero__content {
    margin-top: 3rem;
}

.hero__text {
    max-width: 40ch;
}

.model-2 {
    width: 220px;
    aspect-ratio: 1;
    object-position: top;
    object-fit: cover;
    position: absolute;
    bottom: -2rem;
    left: 5rem;
}

.model-3 {
    width: 200px;
    /* aspect-ratio: 1; */
    /* object-position: top; */
    /* object-fit: cover; */
    position: absolute;
    right: -2.5rem;    
    bottom: 4rem;
}
</style>

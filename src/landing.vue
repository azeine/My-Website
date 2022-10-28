<script setup>
import Button from './components/button.vue'

let vh = window.innerHeight
document.documentElement.style.setProperty('--vh', `${vh}px`);
</script>

<template>
  <main>
    <picture>
      <source type="image/avif" srcset="./assets/images/me.avif"/>
      <source type="image/png" srcset="./assets/images/me.png"/>
      <img src="~/../assets/images/me.png" decoding="async" width="500" height="500" alt="My picture"/>
    </picture>
    <div class="intro">
      <h1 class="greet">Hi There. 👋</h1>
      <h1>I'm Azis Ramadhan</h1>
      <p>Digital Technology Enthusiast & Developer</p>
      <Button text="Contact Me" link='#'/>
    </div>
  </main>
</template>
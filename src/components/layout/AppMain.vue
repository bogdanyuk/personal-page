<template>
  <div class="card-started" id="home-card">
    <div class="profile no-photo">
      <div
        class="slide"
        :style="{
          backgroundImage: 'url(' + require('@/assets/images/bogdan.jpg') + ')',
        }"
      ></div>

      <div class="title">Bogdan Yukhymchuk</div>
      <div class="subtitle subtitle-typed">Fullstack Developer</div>
      <span class="typed-cursor">|</span>

      <!-- profile socials -->
      <div class="social">
        <a target="_blank" href="https://dribbble.com/">
          <span class="fa fa-dribbble"></span>
        </a>
        <a target="_blank" href="https://twitter.com/">
          <span class="fa fa-twitter"></span>
        </a>
        <a target="_blank" href="https://github.com/r3act1st">
          <span class="fa fa-github"></span>
        </a>
        <a target="_blank" href="https://www.spotify.com/">
          <span class="fa fa-spotify"></span>
        </a>
        <a target="_blank" href="https://stackoverflow.com/">
          <span class="fa fa-stack-overflow"></span>
        </a>
      </div>

      <!-- profile buttons -->
      <div class="lnks">
        <a href="#" class="lnk">
          <span class="text">Download CV</span>
        </a>
        <a href="#" class="lnk discover">
          <span class="text">Contact Me</span>
        </a>
      </div>
    </div>
  </div>
</template>
<script>
import { defineComponent } from "@vue/composition-api";
export default defineComponent({
  setup() {},
});
</script>

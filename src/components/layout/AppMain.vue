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
        <a
          target="_blank"
          href=" https://www.linkedin.com/in/bohdan-yukhymchuk/151792172/"
        >
          <span class="fa fa-linkedin"></span>
        </a>
        <a target="_blank" href="https://github.com/r3act1st">
          <span class="fa fa-github"></span>
        </a>
        <a target="_blank" href="https://stackoverflow.com/users/15797612">
          <span class="fa fa-stack-overflow"></span>
        </a>
        <a target="_blank" href="https://www.hackerrank.com/yukhymchb">
          <span class="fab fa-hackerrank"></span>
        </a>
      </div>

      <!-- profile buttons -->
      <div class="lnks">
        <a href="/docs/bohdanyukhymchuk.pdf" class="lnk" target="_blank">
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

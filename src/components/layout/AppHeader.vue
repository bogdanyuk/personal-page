<template>
  <header class="header">
    <div class="profile">
      <div class="title">Bogdan Yukhymchuk</div>
      <div class="subtitle subtitle-typed">Developer</div>
      <span class="typed-cursor">|</span>
    </div>

    <!-- menu btn -->
    <a href="#" class="menu-btn"><span></span></a>

    <!-- menu -->
    <div class="top-menu">
      <ul>
        <li class="active">
          <a href="#about-card">
            <span class="icon ion-person"></span>
            <span class="link">About</span>
          </a>
        </li>
        <li>
          <a href="#resume-card">
            <span class="icon ion-android-list"></span>
            <span class="link">Resume</span>
          </a>
        </li>
        <li>
          <a href="#works-card">
            <span class="icon ion-paintbrush"></span>
            <span class="link">Works</span>
          </a>
        </li>
        <li>
          <a href="#blog-card">
            <span class="icon ion-chatbox-working"></span>
            <span class="link">Blog</span>
          </a>
        </li>
        <li>
          <a href="#contacts-card">
            <span class="icon ion-at"></span>
            <span class="link">Contact</span>
          </a>
        </li>
      </ul>
    </div>
  </header>
</template>
<style scoped>
</style>
<script>
import { defineComponent } from "@vue/composition-api";
export default defineComponent({
  setup() {},
});
</script>

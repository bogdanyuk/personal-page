<template>
  <div class="page new-skin">
    <div class="background gradient">
      <ul class="bg-bubbles">
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
      </ul>
    </div>

    <div
      class="container opened"
      data-animation-in="fadeInLeft"
      data-animation-out="fadeOutLeft"
    >
      <app-header></app-header>
      <app-main></app-main>
      <my-about-us></my-about-us>
      <my-resume></my-resume>
      <my-works></my-works>
      <my-blog></my-blog>
      <my-contact></my-contact>
    </div>

    <div class="s_overlay" style="display: none"></div>
    <my-posts></my-posts>
  </div>
</template>
 <script>
// @ is an alias to /src
import "@/assets/css/animate.css";
import "@/assets/css/ionicons.css";
import "@/assets/css/owl.carousel.css";
import "@/assets/css/magnific-popup.css";

import "@/assets/scss/basic.scss";
import "@/assets/scss/layout.scss";
import "@/assets/scss/blogs.scss";
import "@/assets/scss/gradient.scss";
import "@/assets/scss/new-skin/new-skin.scss";
import "@/assets/scss/demos/demo-1-colors.scss";

import AppHeader from "@/components/layout/AppHeader.vue";
import AppMainVue from "@/components/layout/AppMain.vue";
import AboutVue from "@/components/cards/About.vue";
import ResumeVue from "@/components/cards/Resume.vue";
import BlogVue from "@/components/cards/Blog.vue";
import WorksVue from "@/components/cards/Works.vue";
import ContactVue from "@/components/cards/Contact.vue";
import MyPostsVue from "../components/cards/MyPosts.vue";

export default {
  components: {
    "app-header": AppHeader,
    "app-main": AppMainVue,
    "my-about-us": AboutVue,
    "my-resume": ResumeVue,
    "my-blog": BlogVue,
    "my-works": WorksVue,
    "my-contact": ContactVue,
    "my-posts": MyPostsVue,
  },
};
</script>

<template>
  <div id="app">
    <HeaderVue />
    <SliderVue />
    <div class="center">
      <LastArticlesVue />
      <SidebarVue />
    </div>
    <div class="clearfix"></div>
    <FooterVue />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import MiComponente from "./components/MiComponente.vue";
import HeaderVue from "./components/Header.vue";
import ColoresComponentes from "./components/ColoresComponentes.vue";
import SliderVue from "./components/Slider.vue";
import SidebarVue from "./components/Sidebar.vue";
import LastArticlesVue from "./components/LastArticles.vue";
import FooterVue from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    MiComponente,
    HeaderVue,
    ColoresComponentes,
    SliderVue,
    SidebarVue,
    LastArticlesVue,
    FooterVue,
  },
};
</script>

<style>
@import "./assets/css/styles.css";
</style>

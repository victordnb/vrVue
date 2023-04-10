<template>
  <div id="app">
    <HeaderVue />
    <SliderVue />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MiComponente from './components/MiComponente.vue';
import HeaderVue from './components/Header.vue';
import ColoresComponentes from './components/ColoresComponentes.vue';
import SliderVue from './components/Slider.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    MiComponente,
    HeaderVue,
    ColoresComponentes,
    SliderVue

  }
}
</script>

<style>

@import './assets/css/styles.css'
</style>

<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <ColoresComponentes :color="color"></ColoresComponentes>
  <HeaderVue></HeaderVue>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <MiComponente></MiComponente>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MiComponente from './components/MiComponente.vue';
import HeaderVue from './components/Header.vue';
import ColoresComponentes from './components/ColoresComponentes.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    MiComponente,
    HeaderVue,
    ColoresComponentes

  }
}
</script>

<style>

@import './assets/css/styles.css'
</style>

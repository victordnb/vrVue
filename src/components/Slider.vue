<template>
    <div id="slider" class="slider-big">
        <h1>{{msg}}</h1>
        <a href="#" class="btn-white">Ir al blog</a>
    </div>

</template>

<script>
export default {
  name: "SliderVue",

  data() {
    return {
      msg: "Slider of Vue App",
    };
  },
};
</script>
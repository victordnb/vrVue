<template>
  <div>
    <hr />
    <h1>{{ msg }}</h1>
    <div class="box">
      <h2>Color de componente Header.</h2>
      <h3>{{ color }}</h3>
    </div>
    <hr />
  </div>
</template>

<script>
export default {
  name: "ColoresComponentes",
  props: {
    color: String,
  },
  data() {
    return {
      msg: "ColoresComponentes of Vue App",
    };
  },
};
</script>

<style>
.box {
  color: rgb(228, 170, 170);
}
</style>

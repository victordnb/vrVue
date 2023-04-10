<template>
  <header id="header">
    <div class="center">
      <!-- LOGO -->
      <div id="logo">
        <img src="../assets/logo.png" class="app-logo" alt="Logotipo" />
        <span id="brand"> <strong>Curso</strong>Vue </span>
      </div>

      <!-- MENU -->
      <nav id="menu">
        <ul>
          <li>
            <a href="index.html">Inicio</a>
          </li>
          <li>
            <a href="blog.html">Blog</a>
          </li>
          <li>
            <a href="formulario.html">Formulario</a>
          </li>
          <li>
            <a href="#">Pagina 1</a>
          </li>
          <li>
            <a href="#">Pagina 2</a>
          </li>
        </ul>
      </nav>

      <!--LIMPIAR FLOTADOS-->
      <div class="clearfix"></div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderVue",

  data() {
    return {
      msg: "Cabecera of Vue App",
    };
  },
};
</script>

<style>
header.h1 {
  color: rgb(228, 170, 170);
}
</style>

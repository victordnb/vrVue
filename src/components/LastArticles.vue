<template>
  <section id="content">
    <h2 class="subheader">{{ msg }}</h2>

    <!--Listado articulos-->
    <div id="articles">
      <article class="article-item" id="article-template">
        <div class="image-wrap">
          <img
            src="https://corporativo.leroymerlin.es/documents/60573/19253563/Ilustracion_recopilatorio_01.jpg/b6ae8499-5d3b-a046-a52c-04f720708ae5?t=1672333593014"
            alt="Paisaje"
          />
        </div>

        <h2>Articulo de prueba</h2>
        <span class="date"> Hace 5 minutos </span>
        <a href="#">Leer más</a>

        <div class="clearfix"></div>
      </article>

      <!--AÑADIR ARTICULOS VIA JS-->
    </div>
  </section>
</template>

<script>
export default {
  name: "LastArticlesVue",

  data() {
    return {
      msg: "Últimos artículos de Vue App",
    };
  },
};
</script>

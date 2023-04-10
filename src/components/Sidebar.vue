<template>
  <aside id="sidebar">
    <div id="nav-blog" class="sidebar-item">
      <h3>{{ msg }}</h3>
      <a href="#" class="btn btn-success">Crear artículo</a>
    </div>

    <div id="search" class="sidebar-item">
      <h3>Buscador</h3>
      <p>Encuentra el artículo que buscas</p>
      <form>
        <input type="text" name="search" />
        <input type="submit" name="submit" value="Buscar" class="btn" />
      </form>
    </div>
  </aside>
</template>

<script>
export default {
  name: "SidebarVue",

  data() {
    return {
      msg: "Sidebar of Vue App",
    };
  },
};
</script>

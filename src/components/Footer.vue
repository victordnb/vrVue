<template>
    <footer id="footer">
        <div class="center">
            <h3>{{ msg }}</h3>
            <p>
                &copy; 2023 Curso Vue
            </p>
        </div>
    </footer>


</template>

<script>
export default {
  name: "FooterVue",

  data() {
    return {
      msg: "Footer of Vue App",
    };
  },
};
</script>
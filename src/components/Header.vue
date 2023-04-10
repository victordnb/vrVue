<template>
    <header id="header">
        <div class="center">
            <!-- Logo -->
            <div id="Logo">
                <img src="assets/logo.png" class="app-logo" alt="logoTipo"/>
                <span id="brand">
                    <strong>Curso</strong> Vue
                </span>
            </div>
        </div>

        <!-- Menu -->
        <nav class="menu">
            <ul>
                <li>
                    <a href="#">Inicio</a>
                </li>
                <li>
                    <a href="#">Blog</a>
                </li>
                <li>
                    <a href="#">Formulario</a>
                </li>
                <li>
                    <a href="#">Peliculas</a>
                </li>
                <li>
                    <a href="#">Pagina 1</a>
                </li>
                <li>
                    <a href="#">Pagina 2</a>
                </li>
            </ul>
        </nav>

    </header>

</template>

<script>
export default {
    name: 'HeaderVue',
    
    
    data () {
        return {
        msg: 'Cabecera of Vue App'
        }
    }
}
</script>

<style>
header.h1 {
    color: rgb(228, 170, 170);
}
</style>
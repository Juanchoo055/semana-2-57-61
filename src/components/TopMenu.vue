<template>
        <nav class="navbar navbar-expand-lg sticky-top navbar-dark bg-dark ">
        <a class="navbar-brand " href="/index.html">Sport MAGAZINE
            </a>
        <div class="collapse navbar-collapse justify-content-end " id="navbarNav ">
            <ul class="navbar-nav ">
                <li class="nav-item active ">
                    <a class="nav-link " href="/index.html">Inicio<span class="sr-only ">(current)</span></a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link " href="# ">Servicios</a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link " href="# ">Noticias</a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link " href="# ">Equipo</a>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
    export default {
        name: "TopMenu",
    }
</script>

<style scoped>

.navbar-brand {
  color: black;
  font-size: 28px;
  font-weight: bold;
}

 .nav-link{
  color: rgb(0, 0, 0) !important;
  font-size: large;
}

 .nav-link:hover{
  font-weight: bold;
  color: rgb(204, 39, 39) !important;
  text-decoration: underline !important;

}

.pb {
  color:rgb(204, 176, 17);
  font-size: 25px;
}

 .navbar {
  background-color:rgb(201, 188, 16) !important;
}

</style>

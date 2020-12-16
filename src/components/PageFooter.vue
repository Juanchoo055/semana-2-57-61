<template>

<footer class="page-footer bg-secondary text-white pt-4">

    <!-- Footer Text -->
    <div class="container-fluid text-center text-md-left">

        <!-- Grid row -->
        <div class="row">

            <!-- Grid column -->
            <div class="col-md-8 mt-md-0 mt-3" align="center">

                <!-- Content -->
                <br>
                <h5 class="text-uppercase font-weight-bold">Repositorio</h5>
                <br>
                <a href="https://github.com/Juanchoo055/semana-2-57-61.git"><button type="button" class="btn btn-dark">gitHub</button></a>
                

            </div>
            <!-- Grid column -->

            <hr class="clearfix w-100 d-md-none pb-3">

            <!-- Grid column -->
            <div id= "contenedorredes" class="col-md-4 mb-md-0 mb-3" align="center">

                <!-- Content -->
                <h5 class="text-uppercase font-weight-bold" >Integrantes</h5>
                <li>Juan Giraldo, Scrum Master:  <a href="https://github.com/Juanchoo055" target="_blank">GitHub</a></li>
                <li>Alejandro Sánchez, Desarrollador Frontend:  <a href="https://github.com/asanchezb" target="_blank">GitHub</a></li>
                <li>Carolina Gutiérrez, Desarrollador Backend:  <a href="https://github.com/CarolinaGutierrez1193" target="_blank">GitHub</a></li>
                <li>Kevin Correa, Desarrollador Frontend:  <a href="https://github.com/kevinkc8" target="_blank">GitHub</a></li>
                <li>Julian Gutierrez, Maqueteador:  <a href="https://github.com/Julian-Gutierrez" target="_blank">GitHub</a></li>

            </div>
            <!-- Grid column -->

        </div>
        <!-- Grid row -->

    </div>
    <!-- Footer Text -->

    <!-- Copyright -->
    <div class="footer-copyright text-center py-1 bg-dark">© 2020 Copyright
    </div>
    <!-- Copyright -->

</footer>
</template>

<script>
export default {
    name: "PageFooter"
    
}
</script>

<style scoped>


.footer-copyright{
    background: darkorange;
}

.row{
    background: rgb(0, 0, 0);
}

#contenedorredes {
    text-align:justify;
}

</style>
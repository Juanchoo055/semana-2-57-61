<template>
    <div class="container-fluid">
        <div class="row justify-content-center mb-5">
            <div class="col-sm-6 col-xs-12 col-lg-4 mt-5">
                <div class="card">
                        <div class="d-flex justify-content-center p-2">
                            <div class="col"><img class="img-fluid" src="./images/esports.jpg" width="450" alt=""> 
                            </div>                      
                        </div>          
                                
                            
                    <div class="card-body">
                        <p class="card-text">Noticias de las competiciones de videojuegos multijugador, entre jugadores profesionales. </p>
                        <a href="https://www.espn.com.co/esports/" target="_blank"><button type="button" class="btn btn-dark">Esports</button></a>
                    </div>
                </div>
            
            </div>
            <div class="col-sm-6 col-xs-12 col-lg-4 mt-5">
                <div class="card">
                    <div class="d-flex justify-content-center p-2">
                        <div class="col"><img class="img-fluid" src="./images/noticiadeport.jpg" width="350" alt=""></div>
                    </div>
                    <div class="card-body"> 
                        <p class="card-text">Toda la actualidad de las noticias deportivas a nivel internacional.</p>
                        <a href="https://www.espn.com.co/" target="_blank"><button type="button" class="btn btn-dark">Noticias Deportivas</button></a>
                    </div>
                </div>
            </div>
            <div class="col-sm-6 col-xs-12 col-lg-4 mt-5">
                <div class="card">
                    <div class="d-flex justify-content-center p-2">
                        <div class="col"><img class="img-fluid" src="./images/formula.jpg" width="300" alt="">
                        </div>
                    </div>
                    <div class="card-body">
                        <p class="card-text">Actualidad de la máxima categoría del automovilismo mundial.</p>
                        <a href="https://www.formula1.com/" target="_blank"><button type="button" class="btn btn-dark">Formula 1</button></a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Services"
    
}
</script>

<style scoped>
.card{
    align-items: center;
}
</style>
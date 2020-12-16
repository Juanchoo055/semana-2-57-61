<template>
<div>

    <top-menu></top-menu>

    <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleCaptions" data-slide-to="1" class=""></li>
            <li data-target="#carouselExampleCaptions" data-slide-to="2" class=""></li>
            <li data-target="#carouselExampleCaptions" data-slide-to="3" class=""></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img class="d-block w-100" src="./images/banner.png" alt="First slide" opacity= '0.5;' >
                <rect width="100%" height="100%" fill="#555"></rect>
                <div class="carousel-caption d-none d-md-block">
                <h5 class="pb">El mundo del deporte a tu alcance</h5>
                </div>
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="./images/slide1.jpg" alt="Second slide">
                <rect width="100%" height="100%" fill="#000000."></rect>
                <div class="carousel-caption d-none d-md-block">
                    <h5>Ciclismo</h5>
                </div>
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="./images/slide2.jpg" alt="Second slide">
                <rect width="100%" height="100%" fill="#000000."></rect>
                <div class="carousel-caption d-none d-md-block">
                    <h5>Futbol</h5>
                </div>
            </div>
            <div class="carousel-item">
                <img class="d-block w-100" src="./images/slide3.jpg" alt="Second slide">
                <rect width="100%" height="100%" fill="#000000."></rect>
                <div class="carousel-caption d-none d-md-block">
                    <h5>Tennis</h5>
                </div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
</div>
</template>

<script>

import TopMenu from './TopMenu.vue'
    
    
    export default {
        name: "TopBanner",
        components: { 
            TopMenu 
        },   
    }
</script>

<style scoped>

h5 {
    color:#ffffff ;
}

.pb {
    color:#ffffff;

}



</style>



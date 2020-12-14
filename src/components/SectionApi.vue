<template>
    
        <div class="row mt-md-5 mt-sm-5 mt-xs-5">
    
            <div class="col-lg-6 col-xs-12" v-for="(newss, index) of news" :key="index">
                <div class="d-flex justify-content-center align-items-center">
    
                    <div class="p-3">
                        <img :src="newss.image" alt="imagen news" width="150">
                    </div>
                    
                    <div class="p-2">
                        <h5>{{newss.title}}</h5>
                        <p>
                            <br>
                            {{newss.description}}
                        </p>
                    </div>
    
                </div>
                <div class="d-flex container-fluid justify-content-end pb-2 mt-n2">
                    <a :href="newss.url"  target="_blank" class="btn btn-outline-info">Info</a>
                </div>
            </div>
    
        </div>
    
</template>

<script>

import axios from 'axios';

export default {
    name: "SectionApi",
    data(){
        return{
            news: null
        }
    },
    mounted(){
        axios
        .get('https://gnews.io/api/v4/search?q=sport&max=4&lang=es&token=f24cc55581942a52cb2c934f2baf8888')
        .then(response => {
            (this.news = response.data.articles)
            console.log(this.news)
        })
        
    }
    
}
</script>

<style scoped>

</style>
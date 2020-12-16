<template>
    <div id="app">
  
    <top-banner></top-banner>
    
    <services></services>
    
    <div class="container-fluid">
      <section-api></section-api>
    </div>
    
    <div class="container-fluid">
      <div class="row justify-content-center mb-5">
        <div class="col mt-5" v-for="(item, index) of team" :key="index">
          <team-card v-bind:member="item"></team-card>    
        </div>  
    </div>
    </div>

    
    <page-footer></page-footer>
    
  </div>
</template>

<script>

import PageFooter from './components/PageFooter.vue'
import TeamCard from './components/TeamCard.vue'
import SectionApi from './components/SectionApi.vue'
import TopBanner from './components/TopBanner.vue'
import Services from './components/Services.vue'

export default {
  name: 'App',
  components:{

    TopBanner,
    SectionApi,
    TeamCard,
    PageFooter,
    Services
    
  },

data(){
  return{
    team:[
      {
      codigo: 1088283042,
      nombre: 'Juan Giraldo',
      descripcion: 'Administrador de empresas, Programador',
      rol: 'Scrum Master',
      image: 'https://scontent-bog1-1.xx.fbcdn.net/v/t1.0-9/15337498_10154687746182177_904049445211071438_n.jpg?_nc_cat=104&ccb=2&_nc_sid=09cbfe&_nc_ohc=rZjTq_Y4G6sAX_tA1pY&_nc_ht=scontent-bog1-1.xx&oh=1edf09a119e7b919617270673cd545a9&oe=5FFD26F0'
      },
      {
      codigo: 1030620996,
      nombre: 'Alejandro Sánchez',
      descripcion: 'Ingeniero de Telecomunicaciones',
      rol: 'Desarrollador Frontend',
      image: 'https://bit.ly/38jCuYb'
      },
      {
      codigo: 1057595664,
      nombre: 'Leidy Carolina Gutiérrez Cáceres',
      descripcion: 'Ingeniero electrónico',
      rol: 'Desarrollador backend',
      image: 'https://bit.ly/3oVr438'
      },
      {
      codigo: 1112226772,
      nombre: "Kevin Stiven Correa Rodriguez",
      descripcion: "Técnico en sistemas",
      rol: "Desarrollador Frontend",
      image: "https://scontent-bog1-1.xx.fbcdn.net/v/t1.0-9/84142908_115876526634060_9062243976513323008_o.jpg?_nc_cat=105&ccb=2&_nc_sid=09cbfe&_nc_ohc=xnBUxw_kAnAAX8MKVOI&_nc_oc=AQliSwTScoRDyy_KfTBuO3GjuhJvRiykDRLF0FnOmEF7GzhaJEdAJ3JBnrXfUzVfgRQ&_nc_ht=scontent-bog1-1.xx&oh=fabe285c5b64f8f10f867062f37a5039&oe=5FFC02A2"
      },
      {
      codigo: 1049647135,
      nombre: 'Rosemberg Julian Gutierrez',
      descripcion: 'Programador',
      rol: 'Maqueteador',
      image: 'https://tanzolymp.com/images/default-non-user-no-photo-1.jpg'
      }
    ]
  }}
}
</script>

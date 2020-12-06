<template>
  <div id="app">


    <a name="servicios"></a>
    <div class="card-deck" v-for="(item,index) of servicios" :key="index">
      <ServiciosData v-bind:servicio="item"></ServiciosData>
    </div>



  </div>
</template>

<script>

import ServiciosData from './components/ServiciosData.vue'


export default {
  name: 'App',
  components: {
    ServiciosData
  },
  data(){
  return{
  title
  }
 }
}
</script>


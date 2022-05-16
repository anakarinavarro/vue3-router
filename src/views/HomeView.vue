<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Titulo texto="Pagina de inicio"/>
  </div>
</template>

<script>
import Titulo from '../components/titulo.vue'

export default {
  name: 'HomeView',
  components:{
    Titulo
  }
 
}
</script>

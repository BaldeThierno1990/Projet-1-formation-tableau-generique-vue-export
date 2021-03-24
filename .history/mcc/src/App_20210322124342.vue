<template>
  <div id="app">
  
  <v-header></v-header>
  <v-tableau></v-tableau>
  <v-formation></v-formation>
  
   
  </div>
</template>

<script>
import VTableau from './components/tableau/Vtableau.vue'
import VHeader from './components/menu/VHeader.vue'
import VFormation from './components/tableau/VFormation.vue'
export default {
  name: 'App',
  components: {
  VHeader,
    VTableau,
    VFormation
   
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}

  


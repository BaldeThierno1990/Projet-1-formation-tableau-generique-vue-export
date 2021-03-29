<template>
  <div id="app">
    <v-header></v-header>
   
   <creat-form><creat-form>
   
  </div>
</template>

<script>

import VHeader from "./components/menu/VHeader.vue";


import CreatForm from './components/tableau/Creat-form.vue';

export default {
  name: "App",
  components: {
    VHeader,
    CreatForm,
   
    
  },
};
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
/*Pour tous les appareils équipés d'écrans et dont la taille est inférieure à 780px*/
@media screen and (max-width: 780px){
    body{
        background-color: #848; /*Violet*/
  }
    .conteneur-flex{
        flex-flow: column wrap;
    }
}
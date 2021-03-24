<template>
    <div>
        <h1>Ajouter</h1>
        <div class="form">

        <form @submit.prevent="postData" method="post">
            <!-- <form v-on:submit.prevent="postData"> -->
            <div class="mb-3">
            <label for="mon_id">Formation:</label>
            <input type="text" name="type_formation" class="form-control"  v-model="posts.typeFormation">
            </div>
             <div class="mb-3">
            <label for="mon_id">Lieux:</label>
            <input type="text" name="lieux" class="form-control"  v-model="posts.Lieux"> 
             </div>
              <div class="mb-3">
            <label for="mon_id">Departement:</label>
            <input name="departement" class="form-control"   v-model.number="posts.Departement">
              </div>
               <div class="mb-3">
            <label for="mon_id">Crée le:</label>
            <input type="datetime-local" name="update_at" class="form-control"  v-model="posts.createdAt">
               </div>
                <div class="mb-3">
            <label for="mon_id">Niveau formation:</label>
            <input type="text" name="niveau_formation" class="form-control"  v-model="posts.niveauFormation">
                </div>
                 <div class="mb-3">
            <label for="mon_id">Durée:</label>
            <input name="durée_formation" class="form-control"  v-model.number="posts.dureeFormation">
                 </div>
                  <div class="mb-3">
            <label for="mon_id">Date:</label>
            <input type="date" name="Date" class="form-control"  v-model="posts.Date">
                  </div>
                   <div class="mb-3">
            <label for="mon_id">Mise à jour :</label>
            <input type="datetime-local" name="update_at" class="form-control"  v-model="posts.updateAt">
                   </div>
            <button type="submit">Ajouter</button>
        </form>
    </div>
    </div>
</template>

<script>
import Vue from 'vue'
import axios from 'axios';
import VueAxios from 'vue-axios'
Vue.use(VueAxios, axios)
export default {
    data(){
        return{
            posts:{
                typeFormation:null,
                Lieux:null,
                Date:null,
                Departement:null,
                createdAt:null,
                niveauFormation:null,
                dureeFormation:null,
                updateAt:null,
            },
            
        }
    },
    methods:{
       postData(){
            axios.post('http://127.0.0.1:8000/api/formations', this.posts)

                 .then(() => {
                     //Perform Success Action
                 })
                 .catch(() => {
                     // error.response.status Check status code
                 }).finally(() => {
                     //Perform action in always
                 });
                
        },
    }
}


</script>

<style>
.form{
    margin-right: 100%;
    margin-left: 100px;
}
</style>
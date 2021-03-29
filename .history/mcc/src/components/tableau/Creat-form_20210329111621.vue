<template>
    <div class="vue-tempalte">
        <form>
            <h3>Creer une formation</h3>

            <div class="form-group">
                <label>Composante</label>
                <input type="text" class="form-control form-control-lg"/>
            </div>

            <div class="form-group">
                <label>Localisation</label>
                <input type="local" class="form-control form-control-lg" />
            </div>

            <div class="form-group">
                <label>Type de diplome</label>
                <input type="diplome" class="form-control form-control-lg" />
            </div>
              <div class="form-group">
                <label>Niveau</label>
                <input type="niveau" class="form-control form-control-lg" />
            </div>
              <div class="form-group">
                <label>Domaines</label>
                <input type="domaine" class="form-control form-control-lg" />
            </div>
              <div class="form-group">
                <label>Mention</label>
                <input type="mention" class="form-control form-control-lg" />
            </div>
              <div class="form-group">
                <label>Intitulé formation</label>
                <input type="intitule" class="form-control form-control-lg" />
            </div>
              <div class="form-group">
                <label>Responsable</label>
                <input type="responsable" class="form-control form-control-lg" />
            </div>
              <div class="form-group">
                <label>Statue</label>
                <input type="statue" class="form-control form-control-lg" />
            </div>

            <button type="submit" class="btn btn-dark btn-lg btn-block">Valider</button>

          
        </form>
    </div>
</template>

<script>
    export default {
       data() {
    return {
      form: {
        name: "",
        local: "",
        diplome: " ",
        niveau: " ",
        domaine: " ",
        mention: " ",
        intitulé: " ",
        responsable: " ",
        statue: " "
      }
    };
  },
  
        
      
       methods:{
    checkForm: function (e) {
      if (this.name && this.age) {
        return true;
      }

      this.errors = [];

      if (!this.name) {
        this.errors.push('Name required.');
      }
      if (!this.age) {
        this.errors.push('Age required.');
      }

      e.preventDefault();
    }
  
       }
    }
    
  
    
</script>

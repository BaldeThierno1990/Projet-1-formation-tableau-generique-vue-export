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
                <input type="diplome" class="form-control form-control-lg" />
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
        email: "",
        password: " "
      }
    };
  },
  
        
      }
    
  
    
</script>

<template>
    <div class="form">
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
        name: null,
        local: null,
        diplome: null,
        niveau: null,
        domaine: null,
        mention: null,
        intitule: null,
        responsable: null,
        statue: null
      }
    };
  },
  
        
      
       methods:{
    checkForm: function (e) {
      if (this.name && this.local && this.diplome && this.niveau && this.domaine && this.mention && this.intitule && this.statue) {
        return true;
      }

      this.errors = [];

      if (!this.name) {
        this.errors.push('Name required.');
      }
      if (!this.local) {
        this.errors.push('local required.');
      }
       if (!this.diplome) {
        this.errors.push('diplome required.');
      }
       if (!this.niveau) {
        this.errors.push('niveau required.');

      }
       if (!this.domaine) {
        this.errors.push('domaine required.');
      }
       if (!this.mention) {
        this.errors.push('Mention required.');
      }
       if (!this.intitule) {
        this.errors.push('Intitulé required.');
      }
       if (!this.statue) {
        this.errors.push('statue required.');
      }

      e.preventDefault();
    }
  
       }
    }
    
  
    
</script>

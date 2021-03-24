<template>
   <div id="accordion">
  <div class="card">
    <div class="card-header" id="headingOne">
      <h5 class="mb-0">
        <button class="btn btn-link" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
          Collapsible Group Item #1
        </button>
      </h5>
    </div>

    <div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#accordion">
      <div class="card-body">
       <div class="table">
    <div class="parent">
        <div class="formation">
         <input type="search" id="site-search" name="q"
        aria-label="Search through site content">
        <button>Search</button></div>
        <div class="formation"><button type="button" class="btn btn-info">Créer une Formation</button></div>
          <div class="formation"><button type="button" class="btn btn-success">Exporter une Formation</button></div>
        <div class="formation"><button type="button" class="btn btn-danger">Importer une formation</button></div>

        

    </div>
    

    <div>
        <div class="menu">
        <h1> Mes formations</h1>
    </div>
    <table class="table align-middle">
        
  <thead>
    <tr class="colonne">
      <th scope="col">ID</th>
      <th scope="col">Composante</th>
      <th scope="col">Localisation</th>
      <th scope="col">Type de diplome</th>
      <th scope="col">Niveau</th>
      <th scope="col">Domaines</th>
      <th scope="col">Mention</th>
      <th scope="col">Intitulé formation</th>
      <th scope="col">Responsable</th>
      <th scope="col">Statue</th>
      <th scope="col">Option</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
       <td>Licence Pro</td>
      <td>CY Cergy Paris Université</td>
      <td>Web et Application Mobiles</td>
      <td>Bac+3</td>
      <td>Informatique</td>
      <td>Informatique</td>
      <td>LPW</td>
      <td>Monsieur X</td>
      <td>Ouvert</td>
      <td>
        <button type="button" class="btn btn-danger btn-sm px-3">
          <i class="fas fa-times">X</i>
        </button>
      </td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      
      <td>
        <button type="button" class="btn btn-danger btn-sm px-3">
          <i class="fas fa-times">X</i>
        </button>
      </td>
    </tr>
    <tr>
      <th scope="row">3</th>
       <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td>
        <button type="button" class="btn btn-danger btn-sm px-3">
          <i class="fas fa-times">X</i>
        </button>
      </td>
    </tr>
     
  </tbody>
</table>
        </div>



      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingTwo">
      <h5 class="mb-0">
        <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
          Collapsible Group Item #2
        </button>
      </h5>
    </div>
    <div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#accordion">
      <div class="card-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingThree">
      <h5 class="mb-0">
        <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
          Collapsible Group Item #3
        </button>
      </h5>
    </div>
    <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#accordion">
      <div class="card-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
</div>

</template>
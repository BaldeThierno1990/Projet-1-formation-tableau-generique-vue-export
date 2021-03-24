<template>
   
       
    <!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal">
  Launch demo modal
</button>

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
</template>
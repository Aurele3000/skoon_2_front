<template>
   
  <div class="card">
    <div class="card-image waves-effect waves-block waves-light">
      <img class="activator" src="../assets/media/card1.jpg">
    </div>
    <div class="card-content">
      <span class="card-title activator color: #49ada1;">Evénement Vertou<i class="material-icons right">Ouvrir</i></span>
      <!--<p><a href="#">Link</a></p>-->
    </div>
    <div class="card-reveal">
      <span class="card-title color: #49ada1;">Evénement Vertou<i class="material-icons right">Fermer </i></span>
      <p>Voici la récolte de Vertou...</p>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum quo illum ab rem eaque, repellat qui! Doloremque iste ipsum et doloribus. Voluptates eos amet, tempora est quibusdam vitae quaerat! Cumque nisi commodi tenetur quis iste.</p>
    </div>
  </div> 
  
</template>

<style scoped>
.card {
    width: 400px;
    height: auto;
    float: left;
    margin-left: 50px;
    padding: 10px;
}
.card p {
    font-size: 16px;
    font-weight: 300;   
}
.card span {
    font-family: 'Prompt', sans-serif;
    font-size: 26px;
    font-weight: 400;
    color: #49ada1;   
}
.card i {
    font-size: 16px;
    font-weight: 300;   
}
</style>
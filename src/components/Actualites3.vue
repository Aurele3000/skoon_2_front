<template>
   
  <div class="card">
    <div class="card-image waves-effect waves-block waves-light">
      <img class="activator" src="../assets/media/card3.jpg">
    </div>
    <div class="card-content">
      <span class="card-title activator color: #49ada1;">Evénement St Herblain<i class="material-icons right">Ouvrir</i></span>
      <!--<p><a href="#">Link</a></p>-->
    </div>
    <div class="card-reveal">
      <span class="card-title color: #49ada1;">Evénement St Herblain<i class="material-icons right">Fermer </i></span>
      <p>Voici la récolte de St Herblain...</p>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero recusandae accusamus cupiditate tempore reiciendis perferendis, natus magnam fugit, explicabo dolore nesciunt beatae voluptates expedita illum a est ipsam! Aut eaque maiores magnam, expedita labore ducimus!</p>
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
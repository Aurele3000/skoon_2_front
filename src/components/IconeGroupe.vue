<template>
  <section class="icones">
    <div class="textpol">
      <h1>Comment ça marche</h1>
    </div>
    <div class="groupe1">
      <img
        src="../assets/media/incone-group1.svg"
        alt="Icones de partage"
        style="margin-right: auto; margin-left: auto;"
      />
    </div>

    <div class="groupe">
        <img src="../assets/media/iconeOrdi51.svg" alt="Icone Ordinateur">
        <img src="../assets/media/iconeContact51.svg" alt="Icone Contact">
        <img src="../assets/media/iconeTel51.svg" alt="Icone Téléphone">
        <img src="../assets/media/iconeAgenda51.svg" alt="Icone Agenda">
        <img src="../assets/media/iconeBalai51.svg" alt="Icone Balai">
        </div>
    <hr
      style="
        width: 1450px;
        color: #a94d19;
        height: 1px;
        
        margin-left: auto;
        margin-right: auto;
        margin-top: 50px;
        margin-bottom: 0;
      "
    />
  </section>
</template>

<script>
export default {
  name: "IconeGroupe",
};
</script>

<style scoped>

.groupe {
    display: none;
}
h1 {
  font-size: 48px;
  font-weight: 700;
  font-family: "Prompt", sans-serif;
  text-transform: uppercase;
  color: #49ada1;
  margin-bottom: 20px;
  margin-right: auto;
  margin-left: auto;
}

section {
  margin-top: 40px;

  margin-right: auto;
  margin-left: auto;
  padding: 10px;
}

@media screen and (max-width: 540px) {

    .groupe1 {
        display: none;
    }

      .groupe {
      display: block;
   

  }

    hr{
        
     display: none;

    }

  h1 {
    font-size: 30px;
    font-weight: 700;
    margin-top: -30px;
    padding: 10px;
  }


}
</style>
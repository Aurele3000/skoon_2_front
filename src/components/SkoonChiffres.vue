<template>
  <section class="chiffres">
    <div class="megots" style="float: left; margin-left: 80px">
      <h1>25 000</h1>
      <p>Tonnes de mégots/an <br />rien qu’en France.</p>
    </div>

        <div class="resize">
      <h1>25 000</h1>
      <p>Tonnes de mégots/an <br />rien qu’en France. <br />1 à 2 ans pour la <br /> disparition d’un mégot <br /> dans la nature.</p>
    </div>

    <div class="panneau">
      <img
        src="../assets/media/Panneau1.png"
        alt="Panneau d'interdiction ordures"
        style="
          float: left;
          margin-left: 90px;
          margin-right: 60px;
          margin-top: 10px;
          filter: drop-shadow(5px 5px 5px rgba(0, 0, 0, 0.3));
          padding: 0 0 40px 0
        "
      />
    </div>
    <div class="unadeux">
      <h1>1 à 2</h1>
      <p>Ans pour la disparition <br />d’un mégot dans la nature.</p>
    </div>

        


  </section>
</template>

<script>
export default {
  name: "SkoonChiffres",
};
</script>

<style scoped>
section {
  margin-top: 40px;
margin-left: 40px;


}

.chiffres {
  height: 380px;
  margin-top: 30px;
}

.chiffres h1 {
  font-size: 96px;
  font-weight: 700;
  margin: 0;
}
.chiffres p {
  font-size: 36px;
  font-weight: 500;
}
.resize {
    display: none;
}

@media screen and (max-width: 540px) {
  .chiffres {
    margin-left: -10px;
    margin-top: -30px;
  }
  .panneau {
    padding: 20px;

  }
  .megots {
      display: none;
  }

  .unadeux {
      display: none;
  }

  .resize {
      display: block;
  }

  .chiffres h1 {

      font-size: 60px;
      font-weight: 700;
      margin-bottom: -20px;
      
  }

  .chiffres p {
      font-size: 30px;
      font-weight: 500;
  }

}
</style>
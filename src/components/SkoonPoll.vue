<template>
  <section class="pollution">
    <div>
      <img
        src="../assets/media/plages-nettoyage3.jpg"
        alt="Une main rammasse une bouteille plastique"
        style="
          float: left;
          margin-right: 50px;
          margin-bottom: 50px;
          border-radius: 20px;
          box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.3);
        "
      />
    </div>
    <div class="textpol">
      <h1>La pollution est partout</h1>
      <p>
        nos mers, nos océans, nos fleuves et nos rivières mais aussi dans nos
        forêts, campagnes et villes. Comme nous, tu as dû voir les platanes
        recouverts de sacs plastique, les mégots s’entasser dans les caniveaux,
        les mouchoirs, bouteilles et cannettes choir sur le pavé.
      </p>
    </div>
  </section>
</template>

<script>
export default {
  name: "SkoonPoll",
};
</script>

<style scoped>
h1 {
  font-size: 48px;
  font-weight: 700;
  font-family: "Prompt", sans-serif;
  text-transform: uppercase;
  color: #49ada1;
  margin-bottom: 0;
  margin-top: -21px;
}

section {
  font-size: 36px;
  font-weight: 300;
  color: #a94d19;
  margin-top: 0;
  width: 90%;
  margin-right: auto;
  margin-left: auto;
  padding: 10px;
}

@media screen and (max-width: 540px) {
  p {
    font-size: 20px;
    font-weight: 300;
    margin-right: auto;
    margin-left: auto;
    padding: 10px;
    width: 90%;
    text-align: center;
  }

    h1 {
  font-size: 30px;
  font-weight: 700;
   }
}


</style>
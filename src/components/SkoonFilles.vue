<template>
  <section class="joinus">
    <div>
      <img
        src="../assets/media/petites-filles3.jpg"
        alt="Petites filles sur la plages"
      />
    </div>
    <div class="textjoin">
      <h1>JOINS TOI AUX SKOONER DE FRANCE ET D’AILLEURS</h1>
      <p>
        Parce que la terre est notre responsabilité à tous, parce qu’il n’est
        pas nécessaire d’attendre que nos gouvernements agissent, et surtout
        parce que c’est à la portée de tous. Viens, joins-toi à nous, aide nous
        à rallonger la vie des ours blancs, des perroquets bleus de Patagonie
        mais un peu aussi la tienne.
      </p>
    </div>
  </section>
</template>

<script>
export default {
  name: "SkoonFilles",
};
</script>

<style scoped>
img {
  float: right;
  margin-left: 50px;
  margin-right: 50px;
  margin-bottom: 50px;
  border-radius: 20px;
  box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.3);
}

p {
  font-size: 36px;
  font-weight: 300;
  color: #a94d19;
  font-family: "Prompt", sans-serif;
  margin: 0;
  padding: 15px;

  /*background-color: #FCF8F2;*/
}

h1 {
  font-size: 48px;
  font-weight: 700;
  font-family: "Prompt", sans-serif;
  text-transform: uppercase;
  color: #49ada1;
  margin: 20px;
  

}

section {
  margin-top: 40px;
  margin-right: auto;
  margin-left: auto;
  padding: 0px;
}

@media screen and (max-width: 540px) {
  img {
    display: none;
  }
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
  padding: 10px;
   }
}
</style>
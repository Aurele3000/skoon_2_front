<template>
  <div class="actualites">
    <h1>Actualités</h1>
    <Actualites1 />
    <Actualites2 />
    <Actualites3 />
  </div>
  <div class="cards">
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css"
    />
  </div>
</template>

<script>
import Actualites1 from "../components/Actualites1.vue";
import Actualites2 from "../components/Actualites2.vue";
import Actualites3 from "../components/Actualites3.vue";

export default {
  name: "Actualites",
  components: {
    Actualites1,
    Actualites2,
    Actualites3
  }
};
</script>

<style scoped>
.actualites {
  height: 700px;
  background-color: #fcf8f2;
}

.actualites h1 {
  font-size: 48px;
  font-weight: 600;
  font-family: "Prompt", sans-serif;
}

.card {
  width: 400px;
  height: auto;
  float: left;
  margin-left: 60px;
  padding: 10px;
  margin-top: 50px;
}

@media screen and (max-width: 520px) {
  .card {
    width: 400px;
    height: auto;
    float: left;
    margin-left: 40px;
    padding: 10px;
    margin-top: 30px;
  }

  .actualites {
    height: 1400px;
    background-color: #fcf8f2;
  }
}
</style>

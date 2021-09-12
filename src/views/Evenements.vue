<template>
  <div class="evenements">
    <SkoonAccroche2 />
    <Role />
    <EvenCards />
    
  </div>
  <div class="cards">
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css"
    />
  </div>
</template>

<script>

import SkoonAccroche2 from "../components/SkoonAccroche2.vue";
import EvenCards from "../components/EvenCards.vue";
import Role from "../components/Role.vue";

export default {
  name: "Evenements",
  components: {
    SkoonAccroche2, EvenCards, Role   
  }
};



</script>

<style scoped>
.evenements { 
  height: 2000px;
  background-color: #fcf8f2;
}

.role {
  margin-top: 100px;
}

.cards {

    width: 400px;
    height: auto;
    float: left;
    margin-left: 60px;
    padding: 10px;
    margin-top: 50px;
    

}




</style>



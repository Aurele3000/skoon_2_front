<template>
    <header>
      <div class="imglead">
        <img src="../assets/media/img-lead.jpg" alt="Bouteille plastique sur la plage" style= "width: 1300px; border-radius: 20px; box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.3)"/>
      </div>
            <div class="imglead3">
        <img src="../assets/media/img-lead3.jpg" alt="La plage" style= "border-radius: 20px; box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.3)"/>
      </div>
    </header>
      <div class="accroche">Ensemble<br />sauvons notre planète</div>

</template>

<script>
export default {
    name: 'SkoonAccroche'
}
</script>

<style scoped>

header {

  height: 78px;
  margin-top: 0;
  text-align: center;
  margin-right: auto;
  margin-left: auto;
}

.imglead {
    
  margin-top: 40px;
  
  
}
.imglead3 {
  display: none;
}

.accroche {
  height: 520px;
  text-align: center;
  font-size: 80px;
  font-weight: 600;
  color: #fce72f;
  text-shadow: 5px 5px 5px rgba(0, 0, 0, 0.3);
  font-family: "Prompt", sans-serif;
  text-transform: uppercase;
  line-height: 13 0px;
  margin-right: auto;
  margin-left: auto;
  margin-top: 0;
}

@media screen and (max-width: 540px) {


.imglead {
  display: none;
}

 .imglead3 {
   display: block;
  margin-top: 40px;
  
}

 
  }


</style>
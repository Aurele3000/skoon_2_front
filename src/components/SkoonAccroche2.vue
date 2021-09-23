<template>
    <header>
      <div class="imglead">
        <img src="../assets/media/Balade2.jpg" alt="Réunion avant collecte" style= "width: 1300px; border-radius: 20px; box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.3)"/>
      </div>
      <div class="imglead23">
        <img src="../assets/media/img-lead23.jpg" alt="Surfer" style= "border-radius: 20px; box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.3)"/>
      </div>
    </header>
      <div class="accroche">ça<br />se passe où ?</div>

</template>

<script>
export default {
    name: 'SkoonAccroche2'
}
</script>

<style scoped>

header {

  height: 10px;
  margin-top: 0;
  text-align: center;
  margin-right: auto;
  margin-left: auto;
}

.imglead {
  margin-top: 40px;
}

.imglead23 {
  display: none;
}

.accroche {
  height: 400px;
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
  margin-top: 100px;
}

@media screen and (max-width: 540px) {


.imglead {
  display: none;
}

 .imglead23 {
   display: block;
  margin-top: 40px;  
}

header {

  height: 100px;
  margin-top: 0;
  text-align: center;
  margin-right: auto;
  margin-left: auto;
}

.accroche {
  height: 520px;
  margin-top: 0;
}

 
  }

</style>
<template>

 <footer>
            <div class="plan">
                <h1>Plan du site</h1>
                <connec>
                    <ul>
                        <li><a href="#" title="Home">Home</a></li>
                        <li><a href="#" title="Actualites">Actualités</a></li>
                        <li><a href="#" title="Evenements">Evénements</a></li>
                        <li><a href="#" title="Connexion">Connexion</a></li>
                    </ul>
                </connec>
            </div>
</footer>
    
</template>

<script>
export default {
    name: 'FooterPlan'
}
</script>

<style scoped>

h1 {
    font-size: 48px;
    font-weight: 700;
    font-family: 'Prompt', sans-serif;
    text-transform: uppercase; 
    color: #49ADA1;
    margin-bottom: 20px;
    text-align: center;
    padding: 20px;
}

footer {
    margin-top: 40px;
    margin-right: auto;
    margin-left: auto;
    padding: 10px;
    list-style: none;
}

footer h1 {
margin-left: 40px;
}

connec li {
    display: inline-block;
    text-align: center;
}

connec a {
    font-family: 'Prompt', sans-serif;
    font-size: 36px;
    font-weight: 300; 
    display: block;
    width: 200px;
    color: #a94d19;
    text-decoration: none;
    margin-left: 30px;
    margin-right: 30px;
    text-align: center;
    font-family: 'Prompt', sans-serif;
    font-size: 36px;
    font-weight: 300;    
}

@media screen and (max-width: 540px) {

    .plan {
        margin-right: 30px;
    }
  h1 {
  font-size: 30px;
  font-weight: 700;
  padding: 10px;
  margin-top: -30px;
   }

   connec a {
    
      font-family: "Prompt", sans-serif;
      font-size: 30px;
      font-weight: 400;
      color: #a94d19;
      text-decoration: none;
      list-style: none; 
  
}
}

</style>
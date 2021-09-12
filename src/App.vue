<template>
  <div id="nav">
    <img src="./assets/media/logoskoon3.svg" alt="logo SKOON"/> 
    <router-link to="/">Home</router-link> <router-link to="/actualites">Actualités</router-link> <router-link to="/evenements">Evénements</router-link> <router-link to="/connexion">Connexion</router-link>
  </div>
  <router-view />
</template>

<style>
#app {
  font-family: Prompt, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #a94d19;
  background-color: #fcf8f2;
}

#nav {
  padding: 30px;
  background-color: #fcf8f2;
}
#nav img {
  height: 54px;
  padding: 0 50px;
  margin-top: 0px;
}

#nav a {
  font-size: 36px;
  font-weight: 600;
  color: #49ada1;
  margin: 50px;
  text-decoration: none;
}

#nav a.router-link-exact-active { 
  color: #a94d19;

}

</style>

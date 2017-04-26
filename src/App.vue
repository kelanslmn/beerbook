<template>
  <div id="app">
<div id="description">
<p1>Bienvenue sur le site de revue de bière par excellence "Beerbook"! Pour en apprendre plus ou partager ton expérience sur cette boisson, visites nos différentes pages.</p1>
</div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

  background-image: url(http://dreamicus.com/data/beer/beer-08.jpg);
}

</style>

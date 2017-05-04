<template>
  <div id="app">

    <h1 id="titre"> BeerBook </h1>

    <img src= "src/assets/beerbook.png" id= "logo"/>

    <input id="search" type="text" name="search" placeholder="Recherchez..">


    <h2 id="description"> Bienvenue sur la page "Beerbook"! Ce site héberge des revues de bières afin de vous en apprendre plus et de partager votre savoir sur cette boisson. N'hésitez pas à partager et laisser des commentaires! </h2>

    <div id="resau_sociaux">
      <a id=""></a>
      <img src="src/assets/instagram.png" id="instagram" />
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


  text-align: center;
  color: #2c3e50;

  background-image: url("assets/background.jpg");

}

#titre {
	font-family: Segoe;
	font-size: 100px;
	font-style: normal;
	font-variant: normal;
	font-weight: 400;
	line-height:100px;

}
#search{

background-image: url('assets/recherche.png');
width: 200px;
box-sizing: border-box;
font-size: 20px;
background-position: 5px 5px;
background-repeat: no-repeat;
background-size: 12% auto;
padding: 5px 0px 5px 40px;
border-radius: 10px;
border: 3px solid #ccc;}




#logo {
  position: absolute; top: 20px; left: 20px;
  height: 200px ;
}

#resau_sociaux {
  position: fixed; right: 10px; top: 10px;
}

#instagram {
  height: 30px;
}

</style>

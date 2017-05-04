<template>
  <div id="app">

    <h1 id="titre">BeerBook</h1>

    <img src= "src/assets/beerbook.png" id= "logo"/>

    <form>
      <input id="search" type="text" name="search" placeholder="Recherchez ...">
      <button id="button" type="button">Recherche</button>
    </form>

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
  background-attachment: fixed;
  background-repeat: no-repeat;




}

#titre {
  font-family: Segoe;
  font-size: 100px;
  margin-top: -10px;
  font-weight: 400;
  line-height: 100px;
  padding-top: 50px;

}

form{
  margin-left:auto;
  margin-right:auto;
  box-sizing: border-box;
  border-radius: 10px;
  border: 5px solid #ccc;
  width: 500px;
}

#search{
  background-image: url('assets/recherche.png');
  font-size: 20px;
  background-position: 5px 2px;
  background-repeat: no-repeat;
  background-size: 8% auto;
  padding: 6px 0px 6px 45px;
  margin-left: 0px;
  width: 70%;
  border: none;
  border-radius: 5px 0px 0px 5px;


}

#button{
  background-color: #4CAF50;
  border: none;
  color: white;
  padding: 8px 5px 6px 5px;
  text-align: center;
  font-size: 18px;
  width: auto;
  border-radius: 0px 5px 5px 0px;

}



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

<template>
  <div id="app">
  <br/>
     <h1 id="titre"> BeerBook </h1>

     <input id="search" type="text" name="search" placeholder="Recherchez..">

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

  background-image: url("http://dreamicus.com/data/beer/beer-08.jpg");
  background-attachment:fixed;
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
border: 3px solid #ccc;
}

</style>

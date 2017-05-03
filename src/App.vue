<template>
  <div id="app">
  <br/>
     <h1 id="titre"> BeerBook </h1>
  <img src= "src/assets/beerbook.png" id= "logo"/>


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

#logo {
  position: relative; bottom:170pt; right:330pt;
  height: 250px ;


}

  </style>

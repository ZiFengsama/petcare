<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/About">About</router-link>
	<div id="title">
		<h1>大学生就业平台</h1>
	</div>
  </nav>
  <router-view/>
  
</template>
<!-- <script type="text/javascript">
	// import AboutVue from "./views/AboutView.vue"
	import Duo from "./components/duolie.vue"
	
	export default {
		components:{
			Duo
		}
	}
</script> -->
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
html{
	background-size: 100%;
	
}
nav {
	color: #0000FF;
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}



</style>

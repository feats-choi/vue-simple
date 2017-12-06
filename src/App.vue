<template>
	<div id="app">
		<h3>Example Vue App</h3>
		<Clap></Clap>
	</div>
</template>

<script>
	import Clap from './Clap.vue'
	export default {
    name: 'app',
		components: {
			Clap
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
	}
</style>
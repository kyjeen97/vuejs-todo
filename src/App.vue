<template>
	<div id="app">
		<Header />
	</div>
</template>

<script>
import Header from './components/Header.vue';

export default {
	name: 'App',
		components: {
			Header
		}
	}
</script>

<style lang="scss">
body {
	margin: 0;
	padding: 0;
	background-color: #f3f3f3;

	#app {
		padding: 15px;
		background: #Af1e2d;
	}
}
</style>

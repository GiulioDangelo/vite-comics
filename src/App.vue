<script>
	import AppHeader from "./components/AppHeader.vue";
	import AppBody from "./components/AppBody.vue";
	import AppFoot from "./components/AppFoot.vue";

	export default {
		components: {AppHeader, AppBody, AppFoot},
	};
  
</script>


<template>
	<AppHeader />
	<AppBody />
	<AppFoot />
</template>


<style lang="scss">
@use './assets/style/variables.scss' as *;
*{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-family: sans-serif;
}

</style>
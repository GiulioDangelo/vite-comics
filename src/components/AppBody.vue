<script>
    import AppShop from "./AppShop.vue";

    export default {
		components: {AppShop},
	};
</script>

<template>
    
    <div class="container">
        <h2>Content goes here</h2>
    </div>

    <AppShop/>

</template>

<style scoped lang="scss">
@use './../assets/style/variables.scss' as *;
.container{
    background-color: $main-color;
    height: 200px;
    color: white;
    background-color: black;
}
</style>
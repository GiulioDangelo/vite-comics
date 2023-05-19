<script>
export default{
    props:{
        comicSrc: String,
		title: String,
    }
};
</script>

<template>
    <div class="card">
        <div class="img-container"><img :src="comicSrc" alt=""></div>
        <h4>{{ title }}</h4>
    </div>
</template>


<style lang="scss" scoped>
@use './../assets/style/variables.scss' as *;
img{
    height: 200px;
}

.card{
    width: calc( 100% / 6 );
    text-align: center;
}
</style>
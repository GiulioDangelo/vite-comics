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
        <span>{{ title }}</span>
    </div>
</template>


<style lang="scss" scoped>
@use './../assets/style/variables.scss' as *;
img{
    height: 250px;
}

.card{
    width: calc( 100% / 6 );
    text-align: center;
}
</style>
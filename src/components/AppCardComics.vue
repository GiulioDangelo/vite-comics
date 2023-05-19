<script>
export default{
    props:{
        comicSrc: String,
		title: String,
        price: String,
    }
};
</script>


<template>
    <div class="card">
        <div class="img-container"><img :src="comicSrc" :alt="price"></div>
        <span>{{ title }}</span>
    </div>
</template>


<style lang="scss" scoped>
@use './../assets/style/variables.scss' as *;
img{
    height: 300px;
    padding-bottom: 10px;

    &:hover{
        transform: scale(1.1);
        cursor: pointer;
    }
}

.card{
    width: calc( 100% / 6 );
    text-align: center;
    padding: 10px;
}

span{
    font-size: 18px;
}
</style>
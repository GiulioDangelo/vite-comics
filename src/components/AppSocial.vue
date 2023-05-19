<script></script>


<template>

    <div class="container-social">
        <div class="left">
            <button>SING-UP NOW!</button>
        </div>
    
        <div class="right">
    
            <span>FOLLOW US</span>
    
            <div class="social">
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
    
        </div>
    </div>

</template>

<style scoped lang="scss">
@use './../assets/style/variables.scss' as *;
.container-social{
    @include flex-space-around;
    height: 100px;
    background-color: rgb(48, 48, 48);
}

button{
    border: 2px solid $main-color;
    padding: 13px;
    background-color: rgb(48, 48, 48);
    color: white;
    font-weight: 600;

    &:hover{
        cursor: pointer;
        color: lightgrey
    }
}

.right{
    @include flex-space-around;

    span{
        color: $main-color;
        font-weight: 700;
        margin-right:25px;
    }
        img{
            margin-inline:10px;

            &:hover{
            cursor: pointer;
            transform: scale(1.1);
    }
        }
}
</style>
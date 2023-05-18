<script>
import AppSocial from "./AppSocial.vue";

export default {
    components: {AppSocial},
};
</script>

<template>

    <div class="container">

        <div class="left">
            <div>
                <ul>
                    <li><h3>DC COMIC</h3></li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
    
                <ul>
                    <li><h3>SHOP</h3></li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>

            <ul>
                <li><h3>DC</h3></li>
                <li>Terms Of Use</li>
                <li>Privacy policy(News)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
            </ul>

            <ul>
                <li><h3>SITES</h3></li>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
        </div>

        <div class="right">
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>

    </div>
    <AppSocial/>
</template>

<style scoped lang="scss">
@use './../assets/style/variables.scss' as *;
.container{
    @include flex-space-around;
    background-image: url("../assets/img/footer-bg.jpg");
    height: 450px;
    color: white;
}

.left{
    display: flex;
    justify-content: center;

    ul{
        margin: 30px;
        li{
            list-style: none;
            color: rgb(133, 133, 133);
            margin: 6px 0;

            h3{
                font-size: 25px;
                color: white;
                font-weight: 700;
            }
        }
    }
}

.right{ 
    overflow: hidden;
    height: 100%;
    img{
        height: 700px;
        position: relative;
        bottom: 115px;
    }
}
</style>
<script></script>

<template>

    <div class="main-container">
        <ul>
            <li><img src="../assets/img/buy-comics-digital-comics.png"> <span>DIGITAL COMICS</span> </li>
            <li><img src="../assets/img/buy-comics-merchandise.png"> <span>DC MERCHANDISE</span></li>
            <li><img src="../assets/img/buy-comics-shop-locator.png"> <span>SUBSCRIPTION</span></li>
            <li><img src="../assets/img/buy-comics-subscriptions.png"> <span>COMIC SHOP LOCATOR</span></li>
            <li><img src="../assets/img/buy-dc-power-visa.svg"> <span>DC POWER VISA</span></li>
        </ul>
    </div>

</template>

<style scoped lang="scss">
@use './../assets/style/variables.scss' as *;

.main-container{
    background-color: $main-color;
    height: 200px;
}

ul{
    @include flex-space-around;
    height: 100%;
    list-style: none;
    margin-inline: 100px;

    li{
        display: flex;
        align-items: center;

        span{
            margin-left: 20px;
            color: white;
            font-size: 20px;
        }

        img{
            height: 70px;
        }
    }
}
</style>
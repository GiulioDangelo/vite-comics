<script></script>

<template>

    <div class="container">
        <ul>
            <li><img src="src\assets\img\buy-comics-digital-comics.png">DIGITAL COMICS</li>
            <li><img src="src\assets\img\buy-comics-merchandise.png">DC MERCHANDISE</li>
            <li><img src="src\assets\img\buy-comics-shop-locator.png">SUBSCRIPTION</li>
            <li><img src="src\assets\img\buy-comics-subscriptions.png">COMIC SHOP LOCATOR</li>
            <li><img src="src\assets\img\buy-dc-power-visa.svg">DC POWER VISA</li>
        </ul>
    </div>

</template>

<style scoped lang="scss">
@use './../assets/style/variables.scss' as *;
.container{
    background-color: $main-color;
    height: 200px;
}

ul{
    @include flex-space-around;
    height: 100%;
    list-style: none;
}
</style>
<script></script>

<template>
    <div class="nav">

        <div class="left">
            <img src="src\assets\img\dc-logo.png" alt="" class="logo">
        </div>

        <div class="right">
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </div>

    </div>
</template>

<style scoped lang="scss">
@use './../assets/style/variables.scss' as *;

.nav {
    @include flex-space-around;
    height: 120px;
}

.right {
    height: 100%;
    ul {
        height: 100%;
        @include flex-space-around;
        list-style: none;
        li {
            margin-right: 30px;
            height: 100%;
            display: flex;
            align-items: center;
            font-weight: 600;

            &:hover{
                border-bottom: 8px solid $main-color;
                color:$main-color ;
            }
        }

    }
}
</style>
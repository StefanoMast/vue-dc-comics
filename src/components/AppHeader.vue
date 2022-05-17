<template>
<div class="container">
    <header class="header">
        <div class="logo">
            <img src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="">
        </div>
        <nav>
            <ul class="header__menu">
                <li><a href="">characters</a></li>
                <li><a href="">comics</a></li>
                <li><a href="">movies</a></li>
                <li><a href="">tv</a></li>
                <li><a href="">games</a></li>
                <li><a href="">colletables</a></li>
                <li><a href="">videos</a></li>
                <li><a href="">fans</a></li>
                <li><a href="">news</a></li>
                <li><a href="">shop</a></li>
            </ul>
        </nav>
    </header>
</div>
    
</template>

<script>
export default {
    name: "AppHeader"

}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 1rem;
    &__menu {
        display: flex;
        justify-content: flex-end;
        align-items: center;
    }
    li {
        margin: 0.5rem;
    }
}



</style>
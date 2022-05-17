<template>
  <div class="navMain">
    <div class="container"> 
        <ul class="navMain__menu">
            <li><a href=""><img class="navMain__img" src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="">digital comics</a></li>
            <li><a href=""><img class="navMain__img" src="../assets/vue-dc-comics-1/img/buy-comics-merchandise.png" alt="">dc merchandise</a></li>
            <li><a href=""><img class="navMain__img" src="../assets/vue-dc-comics-1/img/buy-comics-subscriptions.png" alt="">subscription</a></li>
            <li><a href=""><img class="navMain__bigImg" src="../assets/vue-dc-comics-1/img/buy-comics-shop-locator.png" alt="">comic shop locator</a></li>
            <li><a href=""><img class="navMain__bigImg" src="../assets/vue-dc-comics-1/img/buy-dc-power-visa.svg" alt="">dc power visa</a></li>
        </ul>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

.navMain {
    display: flex;
    background-color: rgb(36, 106, 255);
    height: 150px;

    &__menu {
        display: flex;
        justify-content: space-around;
    }

    li {
        margin: 0.5rem;
    }

    a {
        display: flex;
        align-items: center;
    }

    &__img {
        width: 20%;
    }

    &__bigImg {
        width: 15%;
    }
}

</style>
<template>
  <div class="product">
      <img :src="img" alt="">
      <h4>{{ series }}</h4>
  </div>
</template>

<script>
export default {
    name: "AppProduct",
    props: {
        img: String,
        series: String
    }
}
</script>

<style lang="scss" scoped>
.product {
    width: calc(100%/6);
    background-color: black;
    padding: 0.5rem;
    margin: 3rem 0;

    h4 {
        font-size: .8rem;
        color: white;
        text-align: center;
    }

    img {
        width: 100%;
        height: 75%;       
    }


}

</style>
<template>
  <div id="app">
    <!-- header -->
    <AppHeader/>
    <SecondHeader/>
    
    <!-- main -->
    <main>
      <ProductsList/>
      <AppNavMenu/>
      <AppMain/>
    </main>
    <!-- footer -->

  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import SecondHeader from "./components/SecondHeader.vue";
import AppNavMenu from "./components/AppNavMenu.vue";
import AppMain from "./components/AppMain.vue";
import ProductsList from "./components/ProductsList.vue";


export default {
    name: 'App',
    components: {
      AppHeader,
      SecondHeader,
      AppNavMenu,
      AppMain,
      ProductsList
  }
}
</script>

<style lang="scss">
@import "./style/common.scss";

</style>

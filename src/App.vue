<template>
  <div id="app">
    <!-- header -->
    <AppHeader/>
    <AppSecondHeader/>
    
    <!-- main -->
    <main>
      <AppNavMenu/>
      <AppMain/>
    </main>

    <!-- footer -->

  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppSecondHeader from "./components/AppSecondHeader.vue";
import AppNavMenu from "./components/AppNavMenu.vue";
import AppMain from "./components/AppMain.vue";


export default {
    name: 'App',
    components: {
    AppHeader,
    AppSecondHeader,
    AppNavMenu,
    AppMain
}
}
</script>

<style lang="scss">
@import "./style/common.scss";

</style>

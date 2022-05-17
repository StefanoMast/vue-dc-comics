<template>
  <div id="app">
    <!-- header -->
    <AppHeader/>
    <AppSecondHeader/>
    <!-- main -->
    <main>
      questo è main
    </main>

    <!-- footer -->

  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppSecondHeader from "./components/AppSecondHeader.vue";


export default {
    name: 'App',
    components: {
    AppHeader,
    AppSecondHeader
}
}
</script>

<style lang="scss">
@import "./style/common.scss";

</style>

<template>
  <div id="app">
    <div class="container">
      <SiteHeader />
    </div>
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
  },
};
</script>

<style lang="scss">
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container{
    width: 75%;
    margin: auto;
}
</style>

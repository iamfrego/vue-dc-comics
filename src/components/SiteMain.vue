<template>
  <main>
    <div class="black_background">
      <div class="container">
        <h2>Content goes here</h2>
      </div>
    </div>
    <SiteMainIconRow/>
  </main>
</template>

<script>
import SiteMainIconRow from "./SiteMainIconRow.vue"
export default{
    components:{SiteMainIconRow},
}
</script>

<style lang="scss">
@import "../assets/scss/variable.scss";

.black_background {
  background-color: black;
  padding: 4rem;
  h2 {
    color: white;
  }
}

</style>
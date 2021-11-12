<template>
  <div>
    <div class="card">
      <img :src="image" alt="" />
      <h3 class="title">{{ titolo }}</h3>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    image: String,
    titolo: String,
  },
};
</script>

<style lang="scss">
@import "../assets/scss/variable.scss";
    .title{
        padding:1rem 0rem;
        color:$third;
    }
</style>

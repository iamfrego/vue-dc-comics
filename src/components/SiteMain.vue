<template>
  <main>
    <div class="black_background">
      <div class="container">
        <h2>Content goes here</h2>
      </div>
    </div>
    <div class="primary_background flex">
      <div class="cards flex">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <p>DIGITAL COMICS</p>
      </div>
      <div class="cards flex">
        <img src="../assets/img/buy-comics-merchandise.png" alt="" />
        <p>DC MERCHADISE</p>
      </div>
      <div class="cards flex">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
        <p>SUBSCTIPTION</p>
      </div>
      <div class="cards flex">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
        <p>COMIC SHOP LOCATOR</p>
      </div>
      <div class="cards flex">
        <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
        <p>CD POWER VISA</p>
      </div>
    </div>
  </main>
</template>

<script>
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
.primary_background {
  background-color: $brand-primary;
  padding: 3rem;
  justify-content: center;
  .cards {
      line-height: 75px;
      img{
          height: 75px;
          padding-left:2rem ;
      }
      p{
          color: white;
          padding-left: 2rem;
      }
  }
}
</style>
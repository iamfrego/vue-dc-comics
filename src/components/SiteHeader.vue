<template>
  <header>
    <div class="container">
      <nav class="flex">
        <img src="../assets/img/dc-logo.png" alt="" />
        <ul  class="flex"> 
          <li><a href="#">CHARCTERS</a></li>
          <li><a href="#">COMICS</a></li>
          <li><a href="#">MOVIES</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTABLES</a></li>
          <li><a href="#">VIDEOS</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">NEWS</a></li>
          <li><a href="#">SHOP</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/scss/variable.scss";

header {
  margin: 2rem 0rem;


  nav {
    
    justify-content: space-between;
    align-items: center;
  }

  ul {
    li {
      display: inline;
      padding: 1rem;
      a {
        text-decoration: none;
        color: $brand-secondary;
        font-weight: 700;
        &:hover {
          color: $brand-primary;
          border-bottom: $brand-primary 10px solid;
        }
      }
    }
  }
}
</style>

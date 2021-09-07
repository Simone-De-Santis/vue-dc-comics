<template>
  <nav class="container d-flex">
    <div class="logoHeader">
      <img src="@/assets/img/dc-logo.png" alt="DClogo" />
    </div>
    <div class="listHeader">
      <ul class="d-flex">
        <li><a href="#">characteras </a></li>
        <li><a href="#">comics</a></li>
        <li><a href="#">movies</a></li>
        <li><a href="#">tv</a></li>
        <li><a href="#">game</a></li>
        <li><a href="#">collectibles</a></li>
        <li><a href="#">videos</a></li>
        <li><a href="#">fans</a></li>
        <li><a href="#">news</a></li>
        <li><a href="#">shop</a></li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
};
</script>
<style lang="scss" scoped>
.logoHeader {
  img {
    height: 80px;
    margin: 10px 0;
  }
}
.listHeader {
  font-weight: bolder;
}
</style>
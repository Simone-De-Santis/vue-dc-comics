<template>
  <div id="footerListMain">
    <div class="container">
      <ul>
        <li><a href="#" class="title-list"> dc comics</a></li>
        <li><a href="#">characters</a></li>
        <li><a href="#">comics</a></li>
        <li><a href="#">movies</a></li>
        <li><a href="#">tv</a></li>
        <li><a href="#">game</a></li>
        <li><a href="#">videos</a></li>
        <li><a href="#">news</a></li>

        <ul class="second-title-list">
          <li><a href="#" class="title-list"> shop</a></li>
          <li><a href="#">shop DC</a></li>
          <li><a href="#">shop DC collectibles</a></li>
        </ul>
      </ul>

      <ul>
        <li><a href="#" class="title-list"> dc</a></li>
        <li><a href="#">terms of use</a></li>
        <li><a href="#">privacy pokicy(new)</a></li>
        <li><a href="#">ad choices</a></li>
        <li><a href="#">advertising</a></li>
        <li><a href="#">jobs</a></li>
        <li><a href="#">subsciptions</a></li>
        <li><a href="#">talent workshops</a></li>
        <li><a href="#">CPSC Certificates</a></li>
        <li><a href="#">ratings</a></li>
        <li><a href="#">shop help</a></li>
        <li><a href="#">contact us</a></li>
        <li><a href="#">jobs</a></li>
      </ul>
      <ul>
        <li><a href="#" class="title-list">sites</a></li>
        <li><a href="#">DC</a></li>
        <li><a href="#">MAD magazine</a></li>
        <li><a href="#">DC kids</a></li>
        <li><a href="#">DC universe</a></li>
        <li><a href="#">DC power visa</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionListFooter",
};
</script>

<style lang="scss" scoped>
#footerListMain {
  background-image: url("../../assets/img/footer-bg.jpg");
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;

  .container {
    background-image: url("../../assets/img/dc-logo-bg.png");
    background-repeat: no-repeat;
    background-position: right;
    @include center("start-n-center");
    ul {
      margin-right: 20px;
      .title-list {
        font-size: 1.2em;
        text-transform: uppercase;
        color: white;
        font-weight: bolder;
        line-height: 45px;
      }
      .second-title-list {
        margin-top: 35px;
      }
    }
  }
  a {
    color: grey;
    text-transform: capitalize;
    padding: 0;
    line-height: 1.5em;
  }
}
</style> 


 
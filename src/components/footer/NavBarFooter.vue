<template>
  <nav>
    <div class="container">
      <div class="btn">
        <ul>
          <li>
            <a href="#" id="btn-footer">sign-up now!</a>
          </li>
        </ul>
      </div>
      <div>
        <ul class="icon-footer">
          <li id="follow"><a href="#"> follow us</a></li>
          <li>
            <a href="#"
              ><img src="@/assets/img/footer-facebook.png" alt="" />
            </a>
          </li>
          <li>
            <a href="#"
              ><img src="@/assets/img/footer-twitter.png" alt="" />
            </a>
          </li>
          <li>
            <a href="#"
              ><img src="@/assets/img/footer-youtube.png" alt="" />
            </a>
          </li>
          <li>
            <a href="#"
              ><img src="@/assets/img/footer-pinterest.png" alt="" />
            </a>
          </li>
          <li>
            <a href="#"
              ><img src="@/assets/img/footer-periscope.png" alt="" />
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBarFooter",
};
</script>

<style lang="scss" scoped>
nav {
  background-color: #303030;
}
.container {
  @include center("space");
}
.icon-footer {
  @include center();
}
.btn {
  margin: 20px 0;
  border: 1px solid $blue-dc;
  padding: 12px;
  #btn-footer {
    color: white;
    text-decoration: none;
    text-transform: uppercase;

    font-size: 1.2rem;
  }
}
#follow {
  font-weight: bolder;
  text-transform: uppercase;
  font-size: 1.6rem;
  margin-right: 30px;
  a {
    color: $blue-dc;
  }
}
</style>>
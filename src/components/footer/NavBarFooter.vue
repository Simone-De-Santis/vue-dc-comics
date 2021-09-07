<template>
  <nav>
    <div class="container d-flex">
      <div class="btn">
        <ol>
          <li>
            <a href="#" id="btn-footer">sign-up now!</a>
          </li>
        </ol>
      </div>
      <div>
        <ul class="d-flex">
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
.btn {
  margin: 20px 0;
  border: 1px solid #0c70ce;
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
    color: #0c70ce;
  }
}
</style>>
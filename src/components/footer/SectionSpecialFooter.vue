<template>
  <section class="Bg-blue">
    <ol class="d-flex container">
      <li>
        <a class="d-flex" href="#">
          <img
            src="@/assets/img/buy-comics-digital-comics.png"
            alt="buy-comics-digital-comics.png"
          />
          <p>digital comics</p>
        </a>
      </li>
      <li>
        <a class="d-flex" href="#"
          ><img
            src="@/assets/img/buy-comics-merchandise.png"
            alt="merchandise"
          />
          <p>merchandise</p>
        </a>
      </li>
      <li>
        <a class="d-flex" href="#"
          ><img
            src="@/assets/img/buy-comics-subscriptions.png"
            alt="buy-comics-subscriptions.png"
          />
          <p>subscriptions</p>
        </a>
      </li>
      <li>
        <a class="d-flex" href="#"
          ><img
            src="@/assets/img/buy-comics-shop-locator.png"
            alt="buy-comics-subscriptions.png"
          />
          <p>comic shop locator</p>
        </a>
      </li>
      <li>
        <a class="d-flex" href="#"
          ><img
            src="@/assets/img/buy-dc-power-visa.svg"
            alt="buy-dc-power-visa.svg"
          />
          <p>dc power visa</p>
        </a>
      </li>
    </ol>
  </section>
</template>

<script>
export default {
  name: "SectionSpecialFooter",
};
</script>

<style lang="scss" scoped>
.Bg-blue {
  background-color: #0282f9;
  // height: 180px;
}
li {
  padding: 10px;
  a {
    img {
      height: 40px;
    }
    p {
      color: white;
      margin: 20px;
    }
  }
}
</style>
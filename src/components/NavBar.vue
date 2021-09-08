<template>
  <nav class="container">
    <div class="logoHeader">
      <img src="@/assets/img/dc-logo.png" alt="DClogo" />
    </div>
    <div class="listHeader">
      <ul>
        <li v-for="(link, index) in links" :key="index">
          <a :href="link.url" :class="{ active: link.current }">{{
            link.text
          }}</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      links: [
        {
          text: "Characters",
          url: "#",
          current: false,
        },
        {
          text: "Comics",
          url: "#",
          current: true,
        },
        {
          text: "Movies",
          url: "#",
          current: false,
        },
        {
          text: "TV",
          url: "#",
          current: false,
        },
        {
          text: "Games",
          url: "#",
          current: false,
        },
        {
          text: "Collectibles",
          url: "#",
          current: false,
        },
        {
          text: "Videos",
          url: "#",
          current: false,
        },
        {
          text: "Fans",
          url: "#",
          current: false,
        },
        {
          text: "News",
          url: "#",
          current: false,
        },
        {
          text: "Shop",
          url: "#",
          current: false,
        },
      ],
    };
  },
  methods() {},
};
</script>
<style lang="scss" scoped>
.logoHeader {
  img {
    height: 70px;
    margin: 10px 0;
  }
}
.container {
  @include center("space");
  position: relative;
  width: 100%;
  height: 80px;

  .listHeader {
    font-weight: bolder;
    ul {
      @include center();
    }
  }
}
</style>





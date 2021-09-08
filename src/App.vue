<template>
  <div id="app">
    <header>
      <NavBar />
    </header>
    <main>
      <SectionContentMain />
    </main>
    <footer>
      <SectionSpecialFooter />
      <SectionListFooter />
      <NavBarFooter />
    </footer>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
import SectionContentMain from "./components/SectionContentMain.vue";
import SectionSpecialFooter from "./components/footer/SectionSpecialFooter.vue";
import SectionListFooter from "./components/footer/SectionListFooter.vue";
import NavBarFooter from "./components/footer/NavBarFooter.vue";

export default {
  name: "App",
  components: {
    NavBar,
    SectionContentMain,
    SectionSpecialFooter,
    SectionListFooter,
    NavBarFooter,
  },
  data() {
    return {};
  },
  props() {},
  methods() {},
};
</script>

<style  lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "PT Sans Narrow", sans-serif;
}

/*IN App*/
#app {
  /*UTYLITY*/
  .container {
    margin: 0 auto;
    max-width: 1300px;
  }
  header {
    @include fixed-top("");
  }
  main {
    margin-top: 80px;
  }
  ul {
    @include modlist();
  }
}
</style>

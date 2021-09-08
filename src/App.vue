<template>
  <div id="app">
    <header>
      <NavBar />
    </header>
    <main>
      <Jumbo />
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
import NavBar from "./components/NavBar.vue";
import SectionContentMain from "./components/main/SectionContentMain.vue";
import Jumbo from "./components/main/Jumbo.vue";
import SectionSpecialFooter from "./components/footer/SectionSpecialFooter.vue";
import SectionListFooter from "./components/footer/SectionListFooter.vue";
import NavBarFooter from "./components/footer/NavBarFooter.vue";
export default {
  name: "App",
  components: {
    NavBar,
    SectionContentMain,
    Jumbo,
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

  ul {
    @include modlist();
  }
}
</style>

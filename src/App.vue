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
};
</script>

<style  lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: "PT Sans Narrow", sans-serif;
}

/*IN App*/
#app {
  /*UTYLITY*/
  .container {
    margin: 0 auto;
    max-width: 1300px;
  }
  .d-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  li {
    list-style-type: none;
    a {
      padding: 10px;
      color: black;
      text-decoration: none;
      text-transform: uppercase;
    }
  }
  li:hover {
    border-bottom: 2px solid #0c70ce;
  }
}
</style>

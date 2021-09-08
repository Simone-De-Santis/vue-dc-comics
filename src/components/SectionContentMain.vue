<template>
  <main>
    <section>immage jumbo</section>
    <div class="container">
      <div>current series</div>
      <section class="section-comics">
        <div class="card">
          <img
            src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01"
            alt=""
          />
          <fi>American Vampire 1976</fi>
        </div>
      </section>
      <div>load more</div>
    </div>
  </main>
</template>

<script>
export default {
  name: "SectionContentMain",
  data() {
    return {};
  },
  props() {},
  methods() {},
};
</script>

<style scoped lang="scss" >
main {
  min-height: 100px;
  background-color: black;
  color: white;
}
</style>


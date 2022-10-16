<template>
  <main>
    <header>
      <img src="../assets/main.svg" alt="" />
    </header>
    <main>this is the main</main>
    <section>
      <infoCart title="something else" :items="['1', '2', '3']" />
    </section>
    <section></section>
  </main>
</template>

<script>
export default {
  setup() {
    // let title = ref("");
    // let items = ref(["item one", "item two", "item three"]);
    // return { title };
  },
};
</script>

<style></style>

<template>
  <main class="main">
    <section></section>
    <section>
      <Title />
      <info-cart />
    </section>
  </main>
</template>

<script>
export default {};
</script>

<style>
.main InfoCart {
  display: grid;
  grid-template-rows: 3fr 3fr 3fr 3fr;
  padding: 1rem;
  gap: 1rem;
}
section {
  width: 80%;
  height: 70vh;
  border: 1px solid grey;
}
</style>

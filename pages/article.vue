<template>
  <main class="main">
    <section>
      <Title />
    </section>
    <section>3</section>
  </main>
</template>

<script>
export default {};
</script>

<style>
.main {
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

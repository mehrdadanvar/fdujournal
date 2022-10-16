<template>
  <nav class="nav">
    <div class="left">
      <NuxtLink class="link" to="/">Home</NuxtLink>
      <NuxtLink class="link" to="/About">About</NuxtLink>
      <NuxtLink class="link" to="/Authors">For Authors</NuxtLink>
      <NuxtLink class="link" to="/article">Write & Submit</NuxtLink>
    </div>
    <div class="right">
      <NuxtLink class="link" to="/Login">Login</NuxtLink>
      <NuxtLink class="link" to="/Register">Register</NuxtLink>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navigation",
};
</script>

<style scoped>
.nav {
  display: flex;
  padding: 1rem;
  justify-content: space-around;
  border-bottom: 1px solid grey;
}
.link {
  text-decoration: none;
}
.right {
  display: flex;
  gap: 1rem;
}
.left {
  display: flex;
  gap: 1rem;
}
</style>

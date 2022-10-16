<template>
  <div class="title">
    <label for="">Article Title</label>
    <input type="text" name="title" id="" placeholder="type in me" v-model="title" />
  </div>
  <p>{{ title }}</p>
  <button>pressme</button>
</template>

<script setup>
let title = ref("my text not yours but can be your text which eventually will be our text!!!!");
</script>

<style scoped>
/* .mehrdad {
}
input {
  border: none;
  box-shadow: 0 0 20px blue;
  width: 40rem;
  height: 5rem;
} */
</style>

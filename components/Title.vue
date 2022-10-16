<template>
  <div class="title">
    <label for="">Article Title</label>
    <input type="text" name="title" id="" placeholder="type in me" v-model="title" />
  </div>
  <button>pressme</button>
</template>

<script setup></script>

<style scoped>
input {
  border: none;
  box-shadow: 0 0 20px blue;
  width: 40rem;
  height: 5rem;
}
</style>

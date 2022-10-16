<template>
  <div class="cart">
    <h2 class="title" :title="title">{{ title }}</h2>
    <p class="body">
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Et minus quas eius beatae
      consequuntur vero sed quidem eligendi, enim voluptate?
    </p>
    <ul class="bullet" v-for="item in items" :key="item">
      <li>{{ item }}</li>
    </ul>
    <p>footer</p>
  </div>
</template>

<script>
export default {
  props: {
    title: String,
    items: Array,
  },
  setup(props) {
    console.log(props.items);
  },
};
</script>

<style scoped>
* {
  margin: 0;
}
.title {
  background-color: #f72585;
  color: white;
}
.cart {
  display: flex;
  flex-direction: column;
  border: 2px solid #f72585;
  width: 25rem;
  box-sizing: border-box;
  border-radius: 1rem;
  min-height: 20rem;
}
.body {
  padding-left: 1rem;
  color: #4361ee;
}
</style>

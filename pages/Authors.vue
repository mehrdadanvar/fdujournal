<template>
  <main>
    <section class="top">
      <h1>Get your manuscript ready</h1>
    </section>
    <section class="bottom">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus alias, quos sapiente
      temporibus perspiciatis suscipit consequuntur iure itaque praesentium consequatur. Aperiam
      perspiciatis sapiente delectus voluptate optio quis natus cumque tenetur.
    </section>
  </main>
</template>

<script>
export default {
  name: "Authors",
};
</script>

<style>
.top {
  box-sizing: border-box;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #7209b7;
  color: white;
}
.bottom {
  width: 50rem;
  height: 50rem;
  border: 1px solid blue;
  border-radius: 2rem;
  padding: 1rem;
  position: absolute;
  top: 20rem;
  left: 30rem;
  background-color: white;
}
</style>

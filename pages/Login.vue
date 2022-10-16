<template>
  <div class="register">
    <h1>Login</h1>
    <div class="container">
      <form>
        <div class="input-item">
          <label for="">Email Address</label>
          <input type="text" />
        </div>
        <div class="input-item">
          <label for="">Password</label>
          <input type="text" />
        </div>
        <div class="foot">
          <button>Login</button>
          <button><NuxtLink to="/Register">Create an Account</NuxtLink></button>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "Login",
};
</script>

<style></style>

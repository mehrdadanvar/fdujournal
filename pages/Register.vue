<template>
  <main class="register">
    <div class="image"></div>
    <div class="container">
      <form>
        <h1>Register</h1>
        <div class="input-item">
          <label for="">Name</label>
          <input type="text" />
        </div>
        <div class="input-item">
          <label for="">Last Name</label>
          <input type="text" />
        </div>
        <div class="input-item">
          <label for="">email</label>
          <input type="text" />
        </div>
        <div class="input-item">
          <label for="">Password</label>
          <input type="text" />
        </div>
        <div class="input-item">
          <label for=""> confirm Password</label>
          <input type="text" />
        </div>
        <div class="foot">
          <button>Create Account</button>
          <button><NuxtLink to="/Login">I have an Account</NuxtLink></button>
        </div>
      </form>
    </div>
  </main>
</template>

<script>
export default {
  name: "Register",
};
</script>

<style scoped>
.register {
  display: flex;
  flex-direction: row;
  gap: 0rem;
  border-radius: 1rem;
}
.container {
  display: flex;
  border-radius: 1rem;
  padding-left: 2rem;
}
.image {
  width: 20rem;
  height: 40rem;
  background: linear-gradient(45deg, #4361ee, #f72585);
  border-radius: 1rem;
}
.input-item {
  width: 20rem;
  display: flex;
  gap: 0.5rem;
  flex-direction: column;
  padding: 1rem;
  color: #4361ee;
}

input {
  border-radius: 0.5rem;
  height: 2rem;
}
button {
  background-color: #f72585;
  color: white;
  width: 10rem;
  height: 3rem;
  border-radius: 1rem;
  border: none;
}
button:hover {
  box-shadow: 0 0 20px #7209b7;
}
.foot {
  display: flex;
  gap: 1rem;
}
</style>

<template>
  <div id="app">
    <div class="login">
      <login />
    </div>
    
  </div>
</template>

<script>
import Login from "./components/Login.vue";

export default {
  name: "App",
  components: {
    Login,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.login {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>


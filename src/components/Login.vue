<template>
  <section>
    <b-checkbox v-model="hasError">Show errors</b-checkbox>
    <b-field
      label="Username"
      :type="{ 'is-danger': hasError }"
      :message="{ 'Username is not available': hasError }"
    >
      <b-input value="johnsilver" maxlength="30"></b-input>
    </b-field>
    <b-button @click="clickMe">Login</b-button>
  </section>  
</template>

<script>
export default {
  name: "Login",
  data() {
    return {
      hasError: true
    };
  }
};
</script>

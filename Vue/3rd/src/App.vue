<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <UserA />
  <Product />

</template>

<script>
import UserA from './User.vue';
import ProductView from './ProductView.vue';
export default {
  name: 'App',
  components: {
    UserA,
    ProductView
  }
}
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
</style>

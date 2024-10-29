<template>
  <the-header></the-header>
  <router-view></router-view>
</template>

<script>
import TheHeader from './components/nav/TheHeader.vue';
//import productData from "./store/modules/products.js";
//import cartData from "./store/modules/cart.js";

export default {
  components: {
    TheHeader
  },
  
};

</script>

<style>
* {
  box-sizing: border-box;
}

html {
  font-family: sans-serif;
}

body {
  margin: 0;
}
</style>
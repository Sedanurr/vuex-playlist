<template>
  <div id="app">
    <ProductListOne></ProductListOne>
    <ProductListTwo></ProductListTwo>
  </div>
</template>

<script>
import ProductListOne from "./components/productListOne.vue";
import ProductListTwo from "./components/productListTwo.vue";

export default {
  name: "App",
  components: {
    ProductListOne,
    ProductListTwo,
  },
};
</script>
<style>
body {
  font-family: Ubuntu;
  color: #555;
}
</style>

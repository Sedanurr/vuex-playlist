<template>
  <div id="product-list">
    <ProductListOne v-bind:products="products"></ProductListOne>
    <ProductListTwo v-bind:products="products"></ProductListTwo>
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
  data() {
    return {
      products: [
        { name: "Banana skin", price: 20 },
        { name: "Shiny Star", price: 40 },
        { name: "Green Shells", price: 60 },
        { name: "Red Shells", price: 80 },
      ],
    };
  },
};
</script>

<style>
body {
  font-family: Ubuntu;
  color: #555;
}
</style>

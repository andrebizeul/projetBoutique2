<template>
  <div id="app">
    <TheHeader></TheHeader>
    <div class="d-flex flex-row">
      <shop class="w-75"> </shop>
      <cart class="w-25"></cart>
    </div>

  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue';
import Cart from './components/Cart/Cart.vue';
import Shop from './components/Shop/Shop.vue';

export default {
  name: 'App',
  components: {
    TheHeader,
    Shop,
    Cart
  }
}
</script>

<style>

</style>

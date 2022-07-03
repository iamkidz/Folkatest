<template>
  <Detail/>

</template>

<script>
import Login from './components/Login.vue'
import Register from './components/Register.vue'
import Register2 from './components/Register2.vue'
import Product from './components/Product.vue'
import Detail from './components/Detail.vue'

export default {
  name: 'App',
  components: {
    Login,
    Register,
    Register2,
    Product,
    Detail
  }
}


</script>

<style>
  body {
    padding: 0;
    margin: 0;
  }

</style>

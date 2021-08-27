<template>
  <Nav></Nav>
  <Home></Home>
</template>

<script>
import Nav from './components/Nav.vue'
import Home from '@/views/Home/Index.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Home
  }
}
</script>

<style lang="less">
#app {
  font-family: 'Atala',sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
}
</style>

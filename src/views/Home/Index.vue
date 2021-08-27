<template>
  <Header></Header>
  <Main></Main>
  <Footer></Footer>
</template>

<script>

import Footer from '@/components/Footer.vue'
import Header from '@/views/Home/Header.vue'
import Main from '@/views/Home/Main.vue'

export default {
  name:'Home',
  components:{
    Header,
    Main,
    Footer
  }
}
</script>

<style>

</style>
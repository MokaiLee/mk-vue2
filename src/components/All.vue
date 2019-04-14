<template>
  <div>
    <Header></Header>
    <Aside></Aside>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'
import Aside from '@/components/Aside'
export default {
  name: 'all',
  components: {Header, Footer, Aside}
}
</script>

<style scoped>

</style>

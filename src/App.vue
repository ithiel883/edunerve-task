<template>
    <Navbar />
  <Container />
   <Footer /> 
</template>

<script>
import Navbar from './components/Navbar.vue'
import Container from './components/Container.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    Navbar,
    Container,
    Footer
  }
}
</script>

<style>

</style>

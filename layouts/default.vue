<template>
  <div>
    <Nav/>
    <nuxt/>
    <Footer/>
  </div>
</template>

<script>
import Nav from './partials/nav.vue';
import Footer from './partials/footer.vue';

export default {
  components :{
    Nav,
    Footer
  }
}
</script>

<style>

</style>

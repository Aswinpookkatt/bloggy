<template>

  <Header/>
  <router-view />
  <Footer/>

</template>

<script>
import Header from './components/Header';
import Footer from './components/Footer';



export default {
  name: 'App',
  components: {
    Header,
    Footer,
  }
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  font-family:Arial, Helvetica, sans-serif;
}
</style>

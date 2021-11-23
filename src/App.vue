<template>
  <div class="container">
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header"
import Main from "./components/Main"
import Footer from "./components/Footer"

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style>
  .container{
    width: 75%;
    margin: auto;
    text-align: center;
  }
</style>

<template>
  <div id="app">
    <nav-bar></nav-bar>

    <footer-contact></footer-contact>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import FooterContact from "./components/Footer.vue";

export default {
  name: "app",
  components: {
    NavBar,
    FooterContact
  }
};
</script>

<style>
#app {
}
</style>

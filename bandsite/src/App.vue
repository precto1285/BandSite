<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <div class="col s12">
          <nav-bar></nav-bar>
        </div>
      </div>
      <div class="row">
        <div class="col s12">
          <footer-contact></footer-contact>
        </div>
      </div>
    </div>
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

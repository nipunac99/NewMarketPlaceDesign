<template>
  <div>
    <NavBar />
    <slot />
    <Footer />
  </div>
</template>

<script>
import Footer from "./Partials/Footer.vue";
import NavBar from "./Partials/NavBar.vue";

export default {
  name: "AppLayout",
  components: {
    NavBar,
    Footer,
  },
};
</script>

<style></style>

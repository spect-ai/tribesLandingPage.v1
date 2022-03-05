<template>
  <div class="bg">
    <Navbar />
    <Hero />
  </div>
</template>

<script lang="ts">
import Navbar from "./Navbar.vue";
import Hero from "./Hero.vue";
export default {
  name: "Container",
  components: { Navbar, Hero },
};
</script>

<style scoped>
.bg {
  width: 100%;
  height: fit-content;
  min-height: 100vh;
  background-image: linear-gradient(0deg, #00194a 0%, #000 50%);
}
</style>

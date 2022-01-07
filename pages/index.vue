<template>
  <div>
    <!-- <nuxt-link to="/about">About</nuxt-link> -->
    <Nav />
    <h1>Welcome to My Restaurant</h1>
  </div>
  <!-- <Tutorial/> -->
</template>

<script>
import Nav from "~/components/Nav.vue";
export default {
    name: "IndexPage",
    components: { Nav }
}
</script>

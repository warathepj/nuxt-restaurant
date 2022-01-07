<template>
  <div class="m-auto space-y-8">
    <Nav />
    <h1 class="text-center text-2xl">Welcome to My Restaurant</h1>
    <img class="h-96 mx-auto" src="https://images.unsplash.com/photo-1552566626-52f8b828add9?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80" alt="">
    <Footer />
  </div>
</template>

<script>
import Nav from "~/components/Nav.vue";
import Footer from "~/components/Footer.vue";
export default {
    name: "IndexPage",
    components: { Nav, Footer }
}
</script>

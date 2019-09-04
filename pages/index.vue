<template>
  <section class="container">
    <Header />
    <nuxt-link to="/users">The Users</nuxt-link>
    <br />
    <br />
    <br />
    <nuxt-link to="/products">The products</nuxt-link>
    <button @click="$router.push('/products')">Go to Products</button>
  </section>
</template>

<script>
import Logo from "~/components/Logo.vue";
import Header from "~/components/Header.vue";

export default {
  components: {
    Logo,
    Header
  }
};
</script>



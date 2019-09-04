<template>
  <header class="header">
    <ul class="nav-items">
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/users">Users</nuxt-link>
      </li>
    </ul>
  </header>
</template>
<script>
import Header from "@/components/Header";

export default {
  components: {
    Header
  }
};
</script>

<style  scoped>
.header {
  width: 100%;
  height: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #ccc;
}
.nav-items {
  list-style: none;
  padding: 20xp;
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 80%;
}
</style>
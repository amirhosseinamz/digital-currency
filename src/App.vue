<template>
  <Header />
  <router-view />
</template>
<script>
import Header from "./components/layout/Header.vue";
export default {
  name: "app",
  components: {
    // eslint-disable-next-line vue/no-unused-components
    Header,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  body {
    margin: 0;
    padding: 0;
  }
  a {
    text-decoration: none;
  }
  ul {
    list-style: none;
  }
}
</style>

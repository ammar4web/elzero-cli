<script>
import AppHeaderVue from "@/components/global/AppHeaderVue.vue"

export default {
  name: "App",
  components: {
    AppHeaderVue,
  }
}
</script>

<template>
  <div id="app">
    <app-headerVue/>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>

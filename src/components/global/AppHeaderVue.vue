<script>
  export default {
    name: "AppHeaderVue", 
  }
</script>

<template>
  <header>
    <div class="logo">
      <h1>Ammar<span>4web</span></h1>
    </div>
    <nav>
      <!-- 
        tag="li"
        exact
        <a>Home</a>
      -->
      <router-link to="/" tag="li" exact><a>Home</a></router-link>
      <router-link to="/about" tag="li"><a>About</a></router-link>
      <router-link to="/help" tag="li"><a>Help</a></router-link>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
header {
  h1 {
      background-color: #333;
      color: #fff;
      padding: 20px;
  }
}
</style>

<!-- global -->
<style>
* {
  margin: 0;
  padding: 0;
}
</style>
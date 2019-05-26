<template>
  <div id="app">
    <md-toolbar class="md-accent" md-elevation="1" id="nav">
      <h3 class="md-title" style="flex: 1">LOGO</h3>
      <router-link to="/">
        <md-button>Home</md-button>
      </router-link>
      <router-link to="/about">
        <md-button>About</md-button>
      </router-link>
    </md-toolbar>
    <router-view />
  </div>
</template>

<style lang="scss">
body {
  background: #f0f0f0;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;

  .md-layout-container {
    max-width: 1200px;
    width: 100%;
    padding: 0 10px;
    margin: 0 auto;
    display: block;
  }

  .md-card {
    background: #fff;
    margin-bottom: 20px;
  }
}
#nav {
  margin-bottom: 20px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active div.md-button-content {
      color: #3d3d3d;
    }
  }
}
</style>

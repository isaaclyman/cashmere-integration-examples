<template>
  <nav class="nav">
    <div class="nav-brand">
      <a href="#" class="brand">
        <img src="https://cashmere.healthcatalyst.net/assets/TriFlame.svg" />
      </a>
    </div>

    <div class="nav-app">
      <a href="#" class="app">
        <img
          src="https://cashmere.healthcatalyst.net/assets/CashmereAppLogo.svg"
        />
      </a>
    </div>

    <div class="nav-link-container">
      <a href="#" class="nav-link active">
        Home
      </a>
      <a href="#" class="nav-link">
        Oncology
      </a>
    </div>
  </nav>
</template>

<script>
export default {

}
</script>

<style lang="scss">
</style>

<style lang="scss" scoped>
  @import '@healthcatalyst/cashmere/scss/cashmere.scss';

  .nav {
    @include hc-navbar();
  }

  .nav-brand {
    @include navbar-brand();
  }

  .nav-app {
    @include navbar-app();
  }

  .nav-link-container {
    @include hc-navbar-link-container();
  }

  .nav-link {
    @include navbar-link();
  }
</style>

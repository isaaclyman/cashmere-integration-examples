<template>
  <div class="banner banner-info" style="margin-bottom: 8px;">
    <span class="banner-stamp">BETA</span>
    This is a pre-release version of this app and contains experimental
    features.
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  @import '@healthcatalyst/cashmere/scss/cashmere.scss';

  .banner {
    @include hc-banner();
  }

  .banner-info {
    @include hc-banner-info();
  }

  .banner-stamp {
    @include hc-banner-stamp();
    @include hc-banner-info-stamp();
  }
</style>

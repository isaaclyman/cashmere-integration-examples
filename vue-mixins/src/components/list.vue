<template>
  <div class="list">
    <div class="list-item">
      <div class="list-content">
        <span class="icon fa fa-snowflake-o"></span>
        <div class="list-text">
          <h4>List item</h4>
          <span>Second Line</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  @import '@healthcatalyst/cashmere/scss/cashmere.scss';

  $fa-font-path: "~font-awesome/fonts";
  @import '~font-awesome/scss/font-awesome.scss';

  .list {
    @include hc-list();
  }

  .list-item {
    @include hc-list-item();
  }

  .list-content {
    @include hc-list-content();
  }

  .icon {
    @include hc-list-icon();
  }

  .list-text {
    @include hc-list-text();
  }
</style>

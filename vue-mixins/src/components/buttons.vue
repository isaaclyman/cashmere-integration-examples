<template>
  <div>
    <button class="button-prim">
      Primary button (medium)
    </button>
    <button class="button-dest">
      Destructive button (small)
    </button>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  @import '@healthcatalyst/cashmere/scss/cashmere.scss';

  .button-prim {
    @include hc-button();
    @include hc-button-md();
    @include hc-button-primary();
  }

  .button-dest {
    @include hc-button();
    @include hc-button-sm();
    @include hc-button-destructive();
  }
</style>

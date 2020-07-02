<template>
  <div>
    <table class="table">
      <thead>
        <tr>
          <th class="header-cell">
            No.
          </th>
          <th class="header-cell">
            Name
          </th>
        </tr>
      </thead>
      <tbody class="table-body">
        <tr class="row">
          <td class="cell">1</td>
          <td class="cell">Hydrogen</td>
        </tr>
        <tr class="row">
          <td class="cell">2</td>
          <td class="cell">Helium</td>
        </tr>
      </tbody>
      <tfoot class="table-footer">
        <tr class="footer-row">
          <td class="footer-cell">Totals</td>
          <td class="footer-cell">2</td>
        </tr>
      </tfoot>
    </table>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  // An example of including SCSS a la carte
  @import '@healthcatalyst/cashmere/scss/table.scss';

  .table {
    @include hc-table();
    @include hc-bordered-table();
  }

  .header-cell {
    @include hc-table-cell();
    @include hc-table-header-cell();
    @include hc-table-cell-justify-left();
    @include hc-bordered-table-cell();
    @include hc-bordered-table-header-cell();
  }

  .table-body {
    @include hc-table-body();
  }

  .row {
    @include hc-table-body-row();
  }

  .cell {
    @include hc-table-cell();
    @include hc-table-body-cell();
    @include hc-table-cell-justify-left();
    @include hc-bordered-table-cell();
  }

  .table-footer {
    @include hc-table-footer();
  }

  .footer-row {
    @include hc-bordered-table-footer-row();
  }

  .footer-cell {
    @include hc-table-cell();
    @include hc-table-footer-cell();
    @include hc-table-cell-justify-left();
    @include hc-bordered-table-cell();
    @include hc-bordered-table-footer-cell();
  }
</style>

<template>
  <div id="app">
    <Navbar></Navbar>
    <Banner></Banner>

    <div style="padding: 16px;">
      <Buttons></Buttons>
      <List></List>
      <Table></Table>
    </div>
  </div>
</template>

<script>
import Navbar from './components/navbar'
import Banner from './components/banner'
import Buttons from './components/buttons'
import List from './components/list'
import Table from './components/table'

export default {
  name: 'App',
  components: { Navbar, Banner, Buttons, List, Table }
}
</script>

<style lang="scss">
body {
  font-size: 16px;
}
</style>

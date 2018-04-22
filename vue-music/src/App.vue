<template>
  <div id="app">
    <m-header />
    <tab />
  </div>
</template>

<script type="text/ecmascript-6">
  import MHeader from 'components/m-header/m-header'
  import Tab from 'components/tab/tab'
  export default {
    components: {
      MHeader,
      Tab
    }
  }
</script>

<style lang="stylus" rel="stylesheet/stylus" scoped>
  @import "common/stylus/variable"
  #app {
    color: $color-theme
  }
</style>

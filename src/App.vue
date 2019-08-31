<template>
  <div id="app">
    <m-header></m-header>
  </div>
</template>

<script>
import MHeader from './views/m-header/m-header'
export default {
  components:{
    MHeader
  }
}
</script>

<style lang="scss">
@import "common/scss/index.scss";
#app{
  position: fixed;
  top: 0;
  height: 100%;
  width: 100%;
  overflow: hidden;
}
</style>

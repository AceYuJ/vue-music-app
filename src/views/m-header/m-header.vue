<template>
  <div class="m-header">
      <h1 class="text">VMUSIC</h1>
      <div class="mine">
        <i class="iconfont icon-list"></i>
      </div>
      <div class="search">
        <i class="iconfont icon-search"></i>
      </div>
  </div>
</template>

<script>
export default {
  
}
</script>
<style scoped lang="scss">
@import "./../../common/scss/variable.scss";
  .m-header{
    position: relative;
    width: 100%;
    height: 44px;
    text-align: center;
    background: $color-theme;
    .text{
      line-height: 44px;
      font-weight: bold;
      color:$color-text-l;
      letter-spacing: 3px;
    }
    .mine{
      position: absolute;
      top: 0;
      left: 0;
      .iconfont{
        display: block;//将元素转换为块状，使得padding生效
        padding: 11px;
        font-size:22px;
        color:$color-theme-l;
      }
    }
    .search{
      position: absolute;
      top:0;
      right: 0;
      .iconfont{
        display: block;
        padding: 11px;
        font-size: 22px;
        color: $color-theme-l;
      }
    }
  }
</style>

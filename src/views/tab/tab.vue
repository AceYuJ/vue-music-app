<template>
    <div class="tab">
        <div class="tab-item">
            <span>推荐</span>
        </div>
        <div class="tab-item">
            <span>排行</span>
        </div>
        <div class="tab-item">
            <span>歌手</span>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped lang="scss">
    @import "@/common/scss/variable.scss";
    .tab{
        display: flex;
        height: 44px;
        line-height: 44px;
        width: 100%;
        background: $color-theme;
        font-size:$font-size-medium;
        .tab-item{
            text-align: center;
            flex: 1;//如果所有项目的flex-grow属性都为1，则它们将等分剩余空间（如果有的话）
            color:$color-text-lm;
        }
    }
</style>
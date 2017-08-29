<template>
  <div class="m-header">
    <div class="icon"></div>
    <router-link tag="div" class="mine" to="/user">
      <i class="icon-mine"></i>
    </router-link>
  </div>
</template>

<script type="text/ecmascript-6">
  export default {}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "~common/stylus/variable"
  @import "~common/stylus/mixin"

  .m-header
    position: relative
    height: 44px
    color: $color-theme
    font-size: 0
    background:$color-header
    .icon
      display: inline-block
      vertical-align: top
      margin-top: 3px
      margin-left: 12px
      width: 150px
      height: 36px
      bg-image('logo')
      background-size: cover
    .mine
      position: absolute
      top: 0
      right: 0
      .icon-mine
        display: block
        padding: 12px
        font-size: 20px
        color: $color-text
</style>

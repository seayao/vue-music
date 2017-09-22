<template>
  <div id="app" @touchmove.prevent>
    <m-header></m-header>
    <tab></tab>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
    <player></player>
    <confirm ref="confirm" text="PC端浏览器请调成手机模式或者直接用手机浏览器打开。" confirmBtnText="我知道了"></confirm>
  </div>
</template>

<script type="text/ecmascript-6">
  import MHeader from 'components/m-header/m-header'
  import Player from 'components/player/player'
  import Tab from 'components/tab/tab'
  import Confirm from 'base/confirm/confirm'

  export default {
    mounted: function () {
      this.$refs.confirm.show()
    },
    components: {
      MHeader,
      Tab,
      Player,
      Confirm
    }
  }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
</style>

<template>
  <div class="m-header">
    <svg class="topsvg" t="1504056920461" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="1552"><path d="M511.99849 94.087763c16.046893 0 32.018268 0.046317 47.535533 2.400439 10.63483 1.611033 47.116665-18.060683 74.841531-40.729927 21.566693-17.632753 36.113312-39.809625 40.406714-39.304163 15.47699 1.821474-2.979404 103.849181 34.633175 121.519189 158.050363 74.234373 267.528089 234.896622 267.528089 421.058498 0 256.737191-208.206845 464.943029-464.94605 464.943029-256.736184 0-464.944036-208.205838-464.944036-464.943029C47.054454 302.294608 255.262306 94.087763 511.99849 94.087763L511.99849 94.087763zM657.999335 61.437165c-33.040267 36.066994-62.020731 55.043953-105.401814 67.906035-64.118094 19.014213-208.319617 21.857686-200.976329 115.198907C355.704153 296.454614 546.779679 527.863351 605.857254 605.257361c-85.60625-2.484011-167.003677 1.053213-232.442818 60.442926-76.093102 69.05591-99.872951 197.69385-1.708702 266.513139 141.420478 99.128856 384.529339-54.742891 345.348017-215.349761-10.057878-41.230354-38.715129-70.807908-60.352305-105.875055-51.208688-82.870515-102.425431-165.742037-153.640161-248.609531-14.983611-27.468107-18.446324-40.27481-20.856832-71.511728C615.092499 257.639802 700.769232 222.00678 657.999335 61.437165z" p-id="1553" fill="#ffffff"></path></svg>
    <h1 class="app-name">听见好声音</h1>
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
    .topsvg
      display: inline-block
      width: 26px
      height: 26px
      margin-top: 7px
      margin-left: 12px
    .app-name
      display: inline-block
      color: $color-text
      font-size: $font-size-large-x
      vertical-align: top
      line-height: 44px
      margin-left:5px
    .icon
      display: inline-block
      vertical-align: top
      margin-top: 5px
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

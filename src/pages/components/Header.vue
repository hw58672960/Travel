<template>
  <div>
    <div class="header-left">
      <div class="iconfont back-icon">&#xe624;</div>
      返回
    </div>
    <div class="header-input"><span class="iconfont">
      &#xe632;
    </span>输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      <span class="iconfont arrow-icon">
        &#xe65e;
      </span>城市
    </div>
  </div>
</template>

<script>

  export default {
    name: "Header"
  }
</script>

<style lang="stylus" scoped>
  @import "~styles/variables.styl"
  .header
    display: flex
    line-height: .86rem
    background: #00bcd4
    color: #fff

  .header-left
    width: .64rem
    float: left
    .back_icon
      text-align: center
      font-size: .4rem

  .header_input
    flex: 1;
    background: #fff
    line-height: .64rem
    margin-left: .2rem
    padding-left .2rem
    margin-top: .12rem
    border-radius: .1rem
    color: #ccc

    .header-right
      width: 1.24rem
      float: right
    .arrow_icon
      margin-left: -.04rem
      font-size: .24rem

</style>

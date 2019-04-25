<template>
  <div class="icons">
    <div class="icon">
        <div class='icon-img'>
            <img class='icon-img-content' src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" />
        </div>
        <p class="icon-desc">热门景点</p>
    </div>
        <div class="icon">
        <div class='icon-img'>
            <img class='icon-img-content' src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20194/bda58ffc3016edad84e656e8a94b0321.png" />
        </div>
        <p class="icon-desc">广州融创</p>
    </div>
        <div class="icon">
        <div class='icon-img'>
            <img class='icon-img-content' src="http://img1.qunarzz.com/piao/fusion/1804/ff/fdf170ee89594b02.png" />
        </div>
        <p class="icon-desc">深圳必有</p>
    </div>
        <div class="icon">
        <div class='icon-img'>
            <img class='icon-img-content' src="http://img1.qunarzz.com/piao/fusion/1803/50/26ffa31b56646402.png" />
        </div>
        <p class="icon-desc">海洋馆</p>
    </div>
        <div class="icon">
        <div class='icon-img'>
            <img class='icon-img-content' src="http://img1.qunarzz.com/piao/fusion/1803/76/eb88861d78fb9902.png" />
        </div>
        <p class="icon-desc">动植物园</p>
    </div>
        <div class="icon">
        <div class='icon-img'>
            <img class='icon-img-content' src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20194/cba147cf6cfcea7109d0bff6aac6f626.png" />
        </div>
        <p class="icon-desc">深圳动物园</p>
    </div>
        <div class="icon">
        <div class='icon-img'>
            <img class='icon-img-content' src="http://img1.qunarzz.com/piao/fusion/1803/a6/6d97515091789602.png" />
        </div>
        <p class="icon-desc">世界只穿</p>
    </div>
        <div class="icon">
        <div class='icon-img'>
            <img class='icon-img-content' src="http://img1.qunarzz.com/piao/fusion/1803/3e/86314b2af03b7502.png" />
        </div>
        <p class="icon-desc">妈呀说公园</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeIcons'
}
</script>

<style lang="stylus" scoped>
@import '~styles/varibles.styl'
  .icons
    overflow: hidden
    height: 0
    padding-bottom: 50%
    .icon
      position: relative
      overflow: hidden
      width: 25%
      float: left
      height: 0
      padding-bottom: 25%
      .icon-img
        position: absolute
        top: 0
        left: 0
        right: 0
        bottom: 0.44rem
        box-sizing: border-box
        padding: 0.1rem
        .icon-img-content
          display: block
          margin: 0 auto
          height: 100%
      .icon-desc
        position: absolute
        left: 0
        right: 0
        bottom: 0
        height: 0.44rem
        line-height: 0.44rem
        text-align: center
        color: $darkTextColor
</style>

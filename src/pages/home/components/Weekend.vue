<template>
  <div class="title">
    <div>周末去哪儿</div>
    <ul>
      <li class="item border-bottom" v-for="item of recommendList" :key="item.id">
        <div class="item-img-wrapper">
            <img class="item-img" :src="item.imgUrl">
        </div>
        <div class="item-info">
          <p class="item-title">{{item.title}}</p>
          <p class="item-desc">{{item.desc}}</p>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HomeWeekend',
  data () {
    return {
      recommendList: [
        {
          id: '0001',
          imgUrl:
            'http://img1.qunarzz.com/sight/source/1811/15/66f14e0fd6fbb.jpg_r_640x214_5d69f21d.jpg',
          title:
            '深圳欢乐谷狂欢无罪，够胆你就来狂欢无罪，够胆你就来狂欢无罪，够胆你就来',
          desc: '狂欢无罪，够胆你就来！狂欢无罪，够胆你就'
        }, {
          id: '0002',
          imgUrl:
            'http://img1.qunarzz.com/sight/p0/1904/1e/1e51b5ea32ee8033a3.water.jpg_200x200_7750aa0b.jpg',
          title:
            '深圳欢乐谷狂欢无罪，够胆你就来狂欢无罪，够胆你就来狂欢无罪，够胆你就来',
          desc: '狂欢无罪，够胆你就来！狂欢无罪，够胆你就'
        }, {
          id: '0003',
          imgUrl:
            'http://img1.qunarzz.com/sight/source/1811/15/66f14e0fd6fbb.jpg_r_640x214_5d69f21d.jpg',
          title:
            '深圳欢乐谷狂欢无罪，够胆你就来狂欢无罪，够胆你就来狂欢无罪，够胆你就来',
          desc: '狂欢无罪，够胆你就来！狂欢无罪，够胆你就'
        }, {
          id: '0004',
          imgUrl:
            'http://img1.qunarzz.com/sight/source/1811/15/66f14e0fd6fbb.jpg_r_640x214_5d69f21d.jpg',
          title:
            '深圳欢乐谷狂欢无罪，够胆你就来狂欢无罪，够胆你就来狂欢无罪，够胆你就来',
          desc: '狂欢无罪，够胆你就来！狂欢无罪，够胆你就'
        }, {
          id: '0005',
          imgUrl:
            'http://img1.qunarzz.com/sight/source/1811/15/66f14e0fd6fbb.jpg_r_640x214_5d69f21d.jpg',
          title:
            '深圳欢乐谷狂欢无罪，够胆你就来狂欢无罪，够胆你就来狂欢无罪，够胆你就来',
          desc: '狂欢无罪，够胆你就来！狂欢无罪，够胆你就'
        }
      ]
    }
  }
}
</script>

<style lang="stylus" scoped>
@import '~styles/mixins.styl';

.title
  line-height: 0.4rem
  background: #eeeeee
  text-indent: 0.2rem
.item-img-wrapper
  overflow: hidden
  height: 0
  padding-bottom: 33.9%
  .item-img
    width: 100%
.item-info
  padding: 0.1rem
  .item-title
    line-height: 0.54rem
    font-size: 0.32rem
    min-width: 0
    ellipsis()
  .item-desc
    line-height: 0.4rem
    color: #ccc
    ellipsis()
</style>

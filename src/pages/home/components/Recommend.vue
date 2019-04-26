<template>
  <div class="title">
    <div>热销推荐</div>
    <ul>
      <li class="item border-bottom" v-for="item of recommendList" :key="item.id">
        <img class="item-img" :src="item.imgUrl">
        <div class="item-info">
          <p class="item-title">{{item.title}}</p>
          <p class="item-desc">{{item.desc}}</p>
          <button class="item-button">查看详情</button>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HomeRecommend',
  data () {
    return {
      recommendList: [
        {
          id: '0001',
          imgUrl:
            'http://img1.qunarzz.com/sight/p0/1904/1e/1e51b5ea32ee8033a3.water.jpg_200x200_7750aa0b.jpg',
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
            'http://img1.qunarzz.com/sight/p0/1904/1e/1e51b5ea32ee8033a3.water.jpg_200x200_7750aa0b.jpg',
          title:
            '深圳欢乐谷狂欢无罪，够胆你就来狂欢无罪，够胆你就来狂欢无罪，够胆你就来',
          desc: '狂欢无罪，够胆你就来！狂欢无罪，够胆你就'
        }, {
          id: '0004',
          imgUrl:
            'http://img1.qunarzz.com/sight/p0/1904/1e/1e51b5ea32ee8033a3.water.jpg_200x200_7750aa0b.jpg',
          title:
            '深圳欢乐谷狂欢无罪，够胆你就来狂欢无罪，够胆你就来狂欢无罪，够胆你就来',
          desc: '狂欢无罪，够胆你就来！狂欢无罪，够胆你就'
        }, {
          id: '0005',
          imgUrl:
            'http://img1.qunarzz.com/sight/p0/1904/1e/1e51b5ea32ee8033a3.water.jpg_200x200_7750aa0b.jpg',
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

.title {
  line-height: 0.4rem;
  background: #eeeeee;
  text-indent: 0.2rem;
}

.item {
  overflow: hidden;
  display: flex;
  height: 1.9rem;

  .item-img {
    width: 1.7rem;
    height: 1.7rem;
    padding: 0.1rem;
  }

  .item-info {
    flex: 1;
    padding: 0.1rem;
    min-width: 0;

    .item-title {
      line-height: 0.54rem;
      font-size: 0.32rem;
      min-width: 0;
      ellipsis();
    }

    .item-desc {
      line-height: 0.4rem;
      color: #ccc;
      ellipsis();
    }

    .item-button {
      line-height: 0.44rem;
      margin-top: 0.16rem;
      background: #ff9300;
      padding: 0.08rem;
      color: #fff;
    }
  }
}
</style>

<template>
  <view class="myPage">
    <view class="head">
      <view class="avat">
        <u-avatar size="large" :src="src"></u-avatar>
      </view>
      <view class="head-txt">欢迎登陆</view>
    </view>
    <view class="body">
      
    </view>
    <view class="foot">
      <button type="default">退出登陆</button>
    </view>
  </view>
</template>

<script>
  export default {
    data() {
      return {
        src: 'http://pic2.sc.chinaz.com/Files/pic/pic9/202002/hpic2119_s.jpg'
      }
    }
  }
</script>

<style lang="scss" scoped>
  .myPage {
    margin: 0;

    .head {
      width: 100%;
      height: 300rpx;
      // line-height: 300rpx;
      // text-align: center;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
      .avat {
        width: 100%;
        text-align: center;
      }
      .head-txt {
        height: 80rpx;
      }
    }
  }
</style>

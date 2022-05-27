<template>
  <div class="item">
    <div class="header">
      <div class="left">
        <span class="title">热门商品榜</span>
        <span class="time">05-27</span>
      </div>
      <div class="right">
        <span>更多></span>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped lang="less">
.item {
  padding: 0 24px 24px 24px;
  width: 414px;
  height: 404px;
  background: #fff;
  border-radius: 16px;
  box-shadow: 0 2px 8px 0 #d2d7f8;
  .header {
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-pack: justify;
    -ms-flex-pack: justify;
    justify-content: space-between;
    padding: 0;
    height: 55px;
    background: transparent;
    border-bottom: 1px solid rgba(226, 226, 228, 0.5);
    .left {
      width: 100%;
      display: -webkit-box;
      display: -ms-flexbox;
      display: flex;
      -webkit-box-align: center;
      -ms-flex-align: center;
      align-items: center;
      .title {
        display: flex;
        -webkit-box-align: center;
        -ms-flex-align: center;
        align-items: center;
        height: 18px;
        font-size: 18px;
        font-family: PingFangSC, PingFangSC-Regular;
        color: #262626;
        font-weight: 600;
      }
      .time {
        padding-left: 16px;
        font-size: 14px;
        font-family: PingFangSC, PingFangSC-Regular;
        color: #a7a7ad;
      }
    }
    .right {
      padding: 0;
      width: 100px;
      height: 18px;
      background: transparent;
      display: -webkit-box;
      display: -ms-flexbox;

      display: flex;
      justify-content: right;
      > span {
        font-size: 12px;
        font-family: PingFangSC, PingFangSC-Regular;
        color: #a7a7ad;
      }
    }
  }
}
</style>

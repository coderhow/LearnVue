<template>
  <div id="tabbarDiv">
    <div class="bar-item">首页</div>
    <div class="bar-item">分类</div>
    <div class="bar-item">购物车</div>
    <div class="bar-item">我的</div>
  </div>
</template>

<script>
    export default {
        name: "tabbar"
    }
</script>

<style scoped>
  #tabbarDiv {
    display: flex;
    background-color: #f6f6f6;
    position: fixed;
    right: 0;
    left: 0;
    bottom: 0;
    box-shadow: 0 -1px 1px rgba(100,100,100,0.1);
  }
  .bar-item {
    flex : 1;
    text-align: center;
    height: 49px;
  }
</style>

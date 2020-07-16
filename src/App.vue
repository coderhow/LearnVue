<template>
  <div id="app">
    <tabbar>
      <tabbarItem >
        <img slot="item-icon" src="./assets/img/tabbar/home.jpg" alt="">
        <div slot="item-text">首页</div>
      </tabbarItem>
      <tabbarItem >
        <img slot="item-icon" src="./assets/img/tabbar/product.jpg" alt="">
        <div slot="item-text">商品</div>
      </tabbarItem>
      <tabbarItem >
        <img slot="item-icon" src="./assets/img/tabbar/cart.jpg" alt="">
        <div slot="item-text">购物车</div>
      </tabbarItem>
      <tabbarItem >
        <img slot="item-icon" src="./assets/img/tabbar/profile.jpg" alt="">
        <div slot="item-text">我</div>
      </tabbarItem>
    </tabbar>
  </div>
</template>

<script>
  import  tabbar from "./components/tabbar/tabbar";
  import tabbarItem from "./components/tabbar/tabbarItem";
  export default {
    name: 'App',
    components : {
      tabbar,tabbarItem
    }
  }
</script>

<style>
  @import "./assets/css/base.css";
</style>

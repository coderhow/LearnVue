<template>
  <div class="bar-item">
    <slot name="item-icon"></slot>
    <slot name="item-text" ></slot>
  </div>
</template>

<script>
    export default {
        name: "tabbarItem"
    }
</script>

<style scoped>
  .bar-item {
    flex : 1;
    text-align: center;
    height: 49px;
  }
  .bar-item img{
    width: 24px;
    height: 24px;
  }
</style>

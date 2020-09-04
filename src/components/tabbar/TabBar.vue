<template>
    <div id="tab-bar">
      <div class="tab-bar-item">
        <img src="../../assets/images/home.svg" alt="">
        <div>首页</div>
      </div>
      <div class="tab-bar-item">
        <img src="../../assets/images/home.svg" alt="">
        <div>分类</div>
      </div>
      <div class="tab-bar-item">
        <img src="../../assets/images/home.svg" alt="">
        <div>购物车</div>
      </div>
      <div class="tab-bar-item">
        <img src="../../assets/images/home.svg" alt="">
        <div>我的</div>
      </div>
    </div>
</template>

<script>
export default {
    name: "TabBar"
}
</script>

<style scoped>
#tab-bar {
  display: flex;
  background-color: #fff;
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  box-shadow: 0px -3px 3px rgba(100, 100, 100, 0.3);
}
.tab-bar-item {
  flex:1;
  text-align: center;
  height: 49px;
  font-size: 12px;
}
.tab-bar-item img {
  width:30px;
}
</style>

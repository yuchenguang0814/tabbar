<template>
    <div>
      <tab-bar>
        <tab-bar-item path="/home" activeColor="blue">
            <img slot="item-icon" src="../../assets/images/home.svg" alt="">
            <img slot="item-icon-active" src="../../assets/images/home-filling.svg" alt="">
            <div slot="item-text">首页</div>
        </tab-bar-item>
        <tab-bar-item path="/category" activeColor="blue">
            <img slot="item-icon" src="../../assets/images/category-normal.svg" alt="">
            <img slot="item-icon-active" src="../../assets/images/category- Selected.svg" alt="">
            <div slot="item-text">分类</div>
        </tab-bar-item>
        <tab-bar-item path="/cart">
            <img slot="item-icon" src="../../assets/images/shop-normal.svg" alt="">
            <img slot="item-icon-active" src="../../assets/images/shop-Selected.svg" alt="">
            <div slot="item-text">购物车</div>
        </tab-bar-item>
        <tab-bar-item path="/profile">
            <img slot="item-icon" src="../../assets/images/user.svg" alt="">
            <img slot="item-icon-active" src="../../assets/images/user-filling.svg" alt="">
            <div slot="item-text">我的</div>
        </tab-bar-item>
      </tab-bar>
  </div>
</template>

<script>
import TabBar from './TabBar'
import TabBarItem from './TabBarItem'
export default {
  name: 'MainTabBar',
  components: {
    TabBar,
    TabBarItem
  }
}

</script>

<style scoped>

</style>

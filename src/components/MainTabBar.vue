<template>
  <div>
    <tab-bar>
      <tab-bar-item path="/home" activeColor="blue">
        <img slot="item-icon" src="~assets/image/tabbar/home.svg" >
        <img slot="item-icon-active" src="~assets/image/tabbar/home_active.svg" >
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="blue">
        <img slot="item-icon" src="~assets/image/tabbar/category.svg" >
        <img slot="item-icon-active" src="~assets/image/tabbar/category_active.svg" >
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/shopcar" activeColor="blue" >
        <img slot="item-icon" src="~assets/image/tabbar/shopcar.svg" >
        <img slot="item-icon-active" src="~assets/image/tabbar/shopcar_active.svg" >
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile">
        <img slot="item-icon" src="~assets/image/tabbar/profile.svg" >
        <img slot="item-icon-active" src="~assets/image/tabbar/profile_active.svg" >
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>
import TabBar from "components/tabbar/TabBar"
import TabBarItem from "components/tabbar/TabBarItem"
export default {
  components:{
    TabBar,
    TabBarItem
  }
}
</script>

<style>

</style>
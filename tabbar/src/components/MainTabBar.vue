<template>
   <tab-bar>
      <tab-bar-item path="/home" activeColor="skyblue">
        <img slot="item-icon" src="../assets/img/tabbar/kucun.png" alt="">
         <img slot="item-icon-active" src="../assets/img/tabbar/kucunred.png" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="skyblue">
        <img slot="item-icon" src="../assets/img/tabbar/cart.png" alt="">
         <img slot="item-icon-active" src="../assets/img/tabbar/cartred.png" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="skyblue">
        <img slot="item-icon" src="../assets/img/tabbar/renew.png" alt="">
         <img slot="item-icon-active" src="../assets/img/tabbar/renewred.png" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="skyblue"> 
        <img slot="item-icon" src="../assets/img/tabbar/person.png" alt="">
         <img slot="item-icon-active" src="../assets/img/tabbar/personred.png" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
</template>

<script>
import TabBar from "./tabbar/TabBar";
import TabBarItem from "./tabbar/TabBarItem";
export default {
    name:'MainTabBar',
  components: {
    TabBar,
    TabBarItem
  }

}
</script>

<style>

</style>
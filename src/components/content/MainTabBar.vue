<template>
    <tab-bar>
      <tab-bar-item path="/home" activeColor="blue">
        <img slot="item-icon" src="../../assets/img/img_tabbar/index.png" alt="">
        <img slot="item-icon-active" src="../../assets/img/img_tabbar/index-o.png" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="blue">
        <img slot="item-icon" src="../../assets/img/img_tabbar/info.png" alt="">
        <img slot="item-icon-active" src="../../assets/img/img_tabbar/info-o.png" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="blue">
        <img slot="item-icon" src="../../assets/img/img_tabbar/cart.png" alt="">
        <img slot="item-icon-active" src="../../assets/img/img_tabbar/cart-o.png" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/user" activeColor="blue">
        <img slot="item-icon" src="../../assets/img/img_tabbar/user.png" alt="">
        <img slot="item-icon-active" src="../../assets/img/img_tabbar/user-o.png" alt="">  
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar> 
</template>

<script>
  import TabBar from "../common/tabbar/TabBar"
  import TabBarItem from "../common/tabbar/TabBarItem"
  export default {
      name:'MainTabBar',
      components:{
        TabBar,
        TabBarItem
  }
    
}
</script>

<style scoped>

</style>
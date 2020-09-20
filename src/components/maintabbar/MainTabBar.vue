<template>
      <tab-bar>
     <tab-bar-item path="/home">
        <img slot="item-icon" src="../../assets/img/tabbar/home.jpg" alt="">
        <img slot="item-icon-active" src="../../assets/img/tabbar/homeb.jpg" alt="">
        <div slot="item-text" >公司首页</div>
     </tab-bar-item>
     <tab-bar-item path="/profile">
        <img slot="item-icon" src="../../assets/img/tabbar/about.jpg" alt="">
        <img slot="item-icon-active" src="../../assets/img/tabbar/aboutb.jpg" alt="">
        <div slot="item-text" >关于我们</div>
     </tab-bar-item>
     <tab-bar-item path="/product">
        <img slot="item-icon" src="../../assets/img/tabbar/product.jpg" alt="">
        <img slot="item-icon-active" src="../../assets/img/tabbar/productb.jpg" alt="">
        <div slot="item-text" >产品服务</div>
     </tab-bar-item>
     <tab-bar-item path="/contact">
        <img slot="item-icon" src="../../assets/img/tabbar/contact.jpg" alt="">
        <img slot="item-icon-active" src="../../assets/img/tabbar/contactb.jpg" alt="">
        <div slot="item-text" >联系我们</div>
     </tab-bar-item>
    </tab-bar>
</template>

<script>
import TabBar from "../tabbar/TabBar"
import TabBarItem from "../tabbar/TabBarItem"

export default {
    name:"MainTabBar",
components:{
    TabBar,
    TabBarItem
}
}
</script>

<style>

</style>
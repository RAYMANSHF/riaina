<template>
  <div id="app">
    <tab-bar>
     <tab-bar-item>
        <img slot="item-icon" src="./assets/img/tabbar/home.jpg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/homeb.jpg" alt="">
        <div slot="item-text" >公司首页</div>
     </tab-bar-item>
     <tab-bar-item>
        <img slot="item-icon" src="./assets/img/tabbar/about.jpg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/aboutb.jpg" alt="">
        <div slot="item-text" >关于我们</div>
     </tab-bar-item>
     <tab-bar-item>
        <img slot="item-icon" src="./assets/img/tabbar/product.jpg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/productb.jpg" alt="">
        <div slot="item-text" >产品服务</div>
     </tab-bar-item>
     <tab-bar-item>
        <img slot="item-icon" src="./assets/img/tabbar/contact.jpg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/contactb.jpg" alt="">
        <div slot="item-text" >联系我们</div>
     </tab-bar-item>
    </tab-bar>
   </div>
</template>

<script>

import TabBar from "./components/tabbar/TabBar"
import TabBarItem from "./components/tabbar/TabBarItem"

export default {
    name: 'App',
    components:{
      TabBar,
      TabBarItem
    }
  }
</script>

<style>
  @import"./assets/css/base.css";
</style>

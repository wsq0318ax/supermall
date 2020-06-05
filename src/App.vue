<template>
  <div id="app">
    <router-view></router-view>
    <main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
  import MainTabBar from "./components/content/mianTabbar/MainTabBar";
  import TabBar from "./components/common/tabbar/TabBar";

  export default {
    name: 'App',
    components: {
      MainTabBar,
      TabBar

    }
  }
</script>

<style>
  @import "./assets/css/base.css";
</style>

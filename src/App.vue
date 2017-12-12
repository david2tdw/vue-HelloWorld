<template>
  <div id="app">
  	<img src="./assets/logo.png">
  	<h1><a href="#/">开发组件库</a></h1>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="less" scoped>
@import '~vux/src/styles/reset.less';

body {
  background-color: #fbf9fe;
}
</style>

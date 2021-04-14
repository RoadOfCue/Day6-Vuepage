<template>
  <div id="app">
    <header-com></header-com>
    <main-com></main-com>
  </div>
</template>

<script>
import headerCom from './components/headerCom.vue' 
import mainCom from './components/mainCom.vue'

export default {
  name: 'App',
  components: {
    headerCom,mainCom
  }
}
</script>

<style lang="scss">
  $root: 100vw/750 *4;
  *{
    padding: 0;
    margin: 0;
    list-style: none;
    text-decoration: none;
    box-sizing: border-box;
    font-family: PingFangSC-Regular,'Lantinghei SC','Open Sans',Arial,'Hiragino Sans GB','Microsoft YaHei','微软雅黑',STHeiti,'WenQuanYi Micro Hei',SimSun,sans-serif;  
  }

  html{
      font-size: $root;
  }

  #app{
    width: 100%;
    height: 100%;
    background-color: #ffeec0;
    padding-bottom: 20rem;
  }
</style>

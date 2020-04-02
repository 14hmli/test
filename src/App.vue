<template>
  <div id="app">
    <!-- <el-row>
      <el-button>默认按钮</el-button>
      <el-button type="primary">主要按钮</el-button>
      <el-button type="success">成功按钮</el-button>
      <el-button type="info">信息按钮</el-button>
      <el-button type="warning">警告按钮</el-button>
      <el-button type="danger">危险按钮</el-button>
    </el-row>
    <Spinner></Spinner>
    <Scroller height="-100" lock-x>
      <div class="sp"></div>
      <div class="sp"></div>
      <div class="sp"></div>
      <div class="sp"></div>
      <div class="sp"></div>
      <div class="sp"></div>
    </Scroller>
    <img alt="Vue logo" src="./assets/logo.png"> -->
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
// import { Spinner,Scroller } from 'vux'
import Vue from 'vue'


import { Button } from 'element-ui';
Vue.use(Button)

export default {
  name: 'app',
  components: {
    HelloWorld,
    // Spinner,
    // Scroller
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.sp{
  height: 100px;
  width: 200px;
  background: red;
  margin: 20px;
  float: left;
}

</style>

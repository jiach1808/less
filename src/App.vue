<template>
   
  <div id="app">
    <div class="title">vue-cli处理less样式</div>
    <p>size</p>
    <button class="btn">按钮</button>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
     
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="less">

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
 
  margin-top: 60px;
}
.title{
  color:@primary-color;
  font-size: @normal-size;
}
.btn{
  color:@primary-color;

}
p{
  color:red;
  font-size:12px;
}
</style>

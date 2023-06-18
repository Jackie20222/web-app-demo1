<template>

  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->

  
  <div class="common-layout">
    <el-container>
      <el-header>
        <HeaderView msg="Welcome to Your Vue.js App"/>
      </el-header>
      <el-container>
        <el-aside width="200px">Aside</el-aside>
        <el-container>
          <el-main>Main</el-main>
          <el-footer>Footer</el-footer>
        </el-container>
      </el-container>
    </el-container>
  </div>

</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
 import HeaderView from './components/HeaderView.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    HeaderView
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>

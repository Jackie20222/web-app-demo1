<template>

  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->

  
  <div class="common-layout">
    <el-container>
      <el-header>
        <HeaderView msg="Welcome to Your Vue.js App"/>

      </el-header>
      <el-container>
        <el-aside width="200px">
          <!-- Aside -->
          <AsideView msg="Welcome to Your Vue.js App"/>
        </el-aside>
        <el-container>
          <el-main>
            <MainView msg="Welcome to Your Vue.js App"/>
          </el-main>
          <el-footer>
            <FooterView msg="Welcome to Your Vue.js App"/>
          </el-footer>
        </el-container>
      </el-container>
    </el-container>
  </div>

</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
 import HeaderView from './components/HeaderView.vue'
 import AsideView from './components/AsideView.vue'
 import MainView from './components/MainView.vue'
 import FooterView from './components/FooterView.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    HeaderView,AsideView,MainView,FooterView
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

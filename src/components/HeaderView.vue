<template>
<div>
  
    <el-menu mode="horizontal"  background-color="#FF0000" gutter="100">  
      <el-menu-item>a</el-menu-item><el-col :span="6"><div class="grid-content ep-bg-purple" /></el-col>
      <el-menu-item>b</el-menu-item><el-col :span="6"><div class="grid-content ep-bg-purple" /></el-col>
      <el-menu-item>c</el-menu-item><el-col :span="6"><div class="grid-content ep-bg-purple" /></el-col>
    </el-menu>
  </div>
  
</template>

<script>
import { ElMenu, ElMenuItem } from 'element-plus';
export default {
  components: { ElMenu, ElMenuItem }
}
</script>
.el-row {
  margin-bottom: 20px;
}
.el-row:last-child {
  margin-bottom: 0;
}
.el-col {
  border-radius: 4px;
}

.grid-content {
  border-radius: 4px;
  min-height: 36px;
}
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

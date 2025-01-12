<!-- vue-qk-assistant/src/views/Home.vue -->
<template>
  <div>
    <h2>智能助理模块首页</h2>
    <el-button type="primary" @click="showMessage">点击测试</el-button>
  </div>
</template>

<script>
export default {
  name: 'PostsHome',
  methods: {
    showMessage() {
      this.$message('智能助理子应用的 ElementUI 按钮点击了！');
    }
  }
}
</script>
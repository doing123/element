<template>
<section class="test" style="height: 500px;overflow:auto;">
  <div style="height: 1200px;">
    <div>test</div>
    <el-breadcrumb separator="/">
      <el-breadcrumb-item :to="{ path: '/' }">首页</el-breadcrumb-item>
      <el-breadcrumb-item><a href="/">活动管理</a></el-breadcrumb-item>
      <el-breadcrumb-item>活动列表</el-breadcrumb-item>
      <el-breadcrumb-item>活动详情</el-breadcrumb-item>
    </el-breadcrumb>
  </div>
</section>
</template>

<script>
  export default {
    watch: {
      data(val) {
        debugger
      }
    },
    data() {
      return {
        radio: '2'
      };
    },
    methods: {
      handleChange(value) {
        console.log(value);
      }
    }
  };
</script>


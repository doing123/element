<template>
  <div style="margin: 20px;">
    <el-radio v-model="radio" label="1">备选项</el-radio>
    <el-radio v-model="radio" label="2">备选项</el-radio>
  </div>
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


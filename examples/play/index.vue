<template>
<section class="test" style="height: 500px;overflow:auto;">
  <div style="height: 1200px;">
    <div>test</div>
    <el-backtop target=".test"></el-backtop>
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


<template>
  <el-row class="mb-4">
    <el-button>Default</el-button>
    <el-button type="primary">Primary</el-button>
    <el-button type="success">Success</el-button>
    <el-button type="info">Info</el-button>
    <el-button type="warning">Warning</el-button>
    <el-button type="danger">Danger</el-button>
    <el-button>中文</el-button>
  </el-row>
</template>

<script lang="ts" setup>
import { reactive, toRefs, ref } from "vue";
</script>
<style lang="less">
@import url('./assets/styles/index.less');
#app {
  width: 100%;
  height: 100%;
}
</style>

<script setup>
import { ElConfigProvider } from "element-plus";
</script>

<template>
  <el-config-provider size="large">
    <el-form inline>
      <el-form-item label="诉求内容">
        <el-input />
      </el-form-item>
      <el-form-item label="诉求地址">
        <el-input />
      </el-form-item>
      <el-form-item label="诉求来源">
        <el-select />
      </el-form-item>
    </el-form>
  </el-config-provider>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>

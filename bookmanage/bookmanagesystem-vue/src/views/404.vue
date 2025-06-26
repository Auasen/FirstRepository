<script setup>
import router from "@/router/index"
</script>

<template>
  <div style="text-align: center">
    <img src="@/assets/404-01-scaled.webp" alt="404">
    出错了
    <div>
      <el-button type="primary" style="width: 150px; height: 60px; font-size: 20px" @click="router.push('/')">Return</el-button>
    </div>
  </div>
</template>

<style scoped>

</style>
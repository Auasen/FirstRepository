<template>
  <div class="item">
    Vue Online.
  </div>
  <div style="margin-bottom: 30px">
    <RouterLink to="/manage/test">RouterLink Go Through</RouterLink>
    <a href="/test">hyperlink Go Through</a>
  </div>
  <div style="margin-bottom: 30px">
    <el-button type="success" @click="router.push('/test')">push跳转</el-button>
    <el-button type="primary" @click="router.replace('/manage/test')">replace跳转</el-button>
  </div>
</template>

<script setup lang="ts">
import router from "@/router/index.js";
import request from "@/utils/request";
</script>
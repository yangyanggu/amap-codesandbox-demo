<template>
  <div class="main-container">
    <el-amap />
  </div>
</template>

<script setup lang="ts">
import {ElAmap} from '@vuemap/vue-amap'
</script>

<style scoped>
.main-container{
  width: 100vw;
  height: 100vh;
}
</style>

<script setup>
import { ElButton } from 'element-plus'
import { add } from 'missyooo_utils'
</script>

<template>
  <div>
    <el-button @click="add(1, 2)">我是 ElButton</el-button>
  </div>
</template>

<style scoped></style>

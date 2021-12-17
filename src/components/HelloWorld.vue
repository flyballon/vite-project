<script setup lang="ts">
import { ref } from 'vue'
import { ElButton } from 'element-plus'

const count = ref(0)

</script>

<template>

  <el-button type="primary" @click="count++">count is: {{ count }}</el-button>

</template>

<style scoped>

</style>
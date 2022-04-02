<template>
  <div id="logo">
    <el-image :src="src" fit="fill"/>
  </div>
</template>

<script setup>
const src = 'https://cube.elemecdn.com/6/94/4d3ea53c084bad6931a56d5158a48jpeg.jpeg'
</script>

<style scoped>
#logo{
  width: 30px;
  height: 32px;
}
</style>
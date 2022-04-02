<template>
  <div class="common-layout">
    <el-container>
      <el-header id="home-header">
      <Logo></Logo>
      <Breadcrumb></Breadcrumb>
      </el-header>
      <el-container >
        <el-aside width="200px">侧边栏</el-aside>
        <el-main id="home-main">
          <el-header height="80px">筛选框</el-header>
          <el-container>
            内容
          </el-container>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>
<!--样式后续需要重构-->
<script setup>
import Logo from '@/components/header/Logo.vue';
import Breadcrumb from '@/components/header/Breadcrumb.vue';
</script>

<style scoped>
#home-main {
background-color: #f6f6f6;
}
#home-header {
  height:64px;
  display: flex;
  justify-content: space-between;
  text-align: center;
  align-items:center;
}
</style>
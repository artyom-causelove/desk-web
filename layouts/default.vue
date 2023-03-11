<template>
  <app-styles/>
  <el-container>
    <el-aside width="200px">Aside</el-aside>
    <el-container>
      <el-header>Header</el-header>
      <el-scrollbar>
        <el-main style="height: 200vh;">Main</el-main>
      </el-scrollbar>
    </el-container>
  </el-container>
</template>

<style scoped lang="scss">
  .el-container {
    height: 100vh;
  }

  .el-aside {
    border-right: 1px solid var(--el-border-color);
  }

  .el-header {
    border-bottom: 1px solid var(--el-border-color);
  }
</style>

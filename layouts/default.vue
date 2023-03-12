<template>
  <app-styles/>
  <el-container>
    <app-aside/>
    <el-container direction="vertical">
      <app-header/>
      <el-scrollbar>
        <el-main><slot/></el-main>
      </el-scrollbar>
    </el-container>
  </el-container>
</template>

<style scoped lang="scss">
  .el-container {
    height: 100vh;
  }

  .el-main {
    padding-top: 10px;
  }
</style>

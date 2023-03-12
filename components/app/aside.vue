<template>
  <el-aside width="200px">
    <el-space fill direction="vertical" :size="60">
      <div></div>
      <el-menu router>
          <el-menu-item index="/namespaces">
            <el-icon><House/></el-icon>
            <span>Namespaces</span>
          </el-menu-item>
          <el-menu-item index="/projects">
            <el-icon><Menu/></el-icon>
            <span>Projects</span>
          </el-menu-item>
      </el-menu>
    </el-space>
  </el-aside>
</template>

<style scoped lang="scss">
  .el-space {
    width: 100%;
  }

  .el-aside {
    border-right: 1px solid var(--el-border-color);
  }

  .el-menu {
    border-right: 0;

    &-item {
      font-size: var(--el-font-size-ex);

      .el-icon {
        font-size: var(--el-font-size-medium);
      }
    }
  }
</style>

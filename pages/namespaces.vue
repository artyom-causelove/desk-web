<template>
  <el-tabs model-value="exist">
    <el-tab-pane name="exist" label="Your namespaces">AWD</el-tab-pane>
    <el-tab-pane name="creating">
      <template #label>
        <span class="custom-tabs-label">
          <el-icon><plus/></el-icon>
          <span>Create new one</span>
        </span>
      </template>
      <app-namespace-create/>
    </el-tab-pane>
  </el-tabs>
</template>

<style scoped lang="scss">
.custom-tabs-label .el-icon {
  vertical-align: middle;
}
.custom-tabs-label span {
  vertical-align: middle;
  margin-left: 4px;
}
</style>

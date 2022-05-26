<template>
  <div class="dashboard-container">
    <div class="dashboard-text">Activiti 流程管理系统</div>
    <a href="http://localhost:8079/#/home"><el-button type="primary" style="width: 250px">返回OA系统</el-button> </a>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>

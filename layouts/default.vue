<template>
  <el-container class="layout-default">
    <el-header class="el-header">
      <MyHeader />
    </el-header>
    <el-main>
      <nuxt />
    </el-main>
    <el-footer height="100%">
      <MyFooter />
    </el-footer>
  </el-container>
</template>

<script>
import MyHeader from '../components/public/header/index'
import MyFooter from '@/components/public/footer/index.vue'
export default {
  components: {
    MyHeader,
    MyFooter
  }
}
</script>
<style lang="css" scoped>
.el-header {
  height: auto !important;
}
</style>

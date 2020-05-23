<template>
  <el-row class="m-header">
    <el-col :span="5">
      <geo />
    </el-col>
    <el-col :span="5">
      <user></user>
    </el-col>
    <el-col :span="14">
      <navber></navber>
    </el-col>
  </el-row>
</template>

<script>
import Geo from './geo'
import User from './user'
import Navber from './nav'
export default {
  components: {
    Geo,
    User,
    Navber
  }
}
</script>

<style lang="scss">
@import '@/assets/css/public/header/index.scss';
</style>
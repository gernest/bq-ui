<template>
    <el-aside>
        <el-menu default-active="1" class="el-menu-vertical-demo" @open="handleOpen" @close="handleClose" :collapse="isCollapse">
            <el-menu-item index="1">
                <i class="el-icon-menu"></i>
                <span slot="title">BQ</span>
            </el-menu-item>
            <el-menu-item index="2">
                <i class="el-icon-question"></i>
                <span slot="title">About&Features</span>
            </el-menu-item>
            <el-menu-item index="3">
                <i class="el-icon-download"></i>
                <span slot="title">Download</span>
            </el-menu-item>
        </el-menu>
    </el-aside>
</template>
<style>
</style>
<script>
export default{
  data () {
    return {
      isCollapse: true
    }
  },
  methods: {
    handleOpen (key, keyPath) {
      console.log(key, keyPath)
    },
    handleClose (key, keyPath) {
      console.log(key, keyPath)
    }
  }
}
</script>
<template>
  <div id="app">
    <el-container>
      <side-nav>
        <title>BQ</title>
      </side-nav>
      <el-main>
        <router-view/>
      </el-main>
    </el-container>
  </div>
</template>
<script>
export default {
  name: 'app'
}
</script>

<style>
</style>

<template>
  <el-container class="container">
    <el-header class="middle">Header</el-header>
    <el-container>
      <el-aside width="200px" class="aside">Aside</el-aside>
      <el-main class="main">Main</el-main>
    </el-container>
  </el-container>
</template>

<script>
export default {
    data() {
        return {
            
        }
    },
};
</script>

<style>
.container {
  height: 100%;

  background: #b3c0d1;
}
.middle {
  text-align: center;
  line-height: 60px;
}
.aside {
  background: red;
}
.main {
  background: blue;
}
.loginout {
  line-height: 60px;
  text-decoration: none;
}
</style>

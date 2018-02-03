<template>
  <div id="header">
    <el-col>
      <el-menu :default-active="path" class="el-menu-demo" mode="horizontal" theme="dark">
        <el-menu-item index="/upload_img">图片上传</el-menu-item>
        <el-menu-item index="/upload_video">视频上传</el-menu-item>
        <el-menu-item index="/https">网络请求</el-menu-item>
        <el-menu-item index="/other">其他</el-menu-item>
      </el-menu>
    </el-col>
  </div>
</template>

<script>
    export default {
        name: "header",
        data: function () {
          return {
            path: '/upload_img'
          }
        },
        methods: {

        }
    }
</script>

<style scoped>

</style>

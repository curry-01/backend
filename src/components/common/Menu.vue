<template>
  <div class="navbar">
    <el-menu theme="dark" router unique-opened>
      <div class="navbar-logo"></div>
      <div class="navbar-menu">
        <el-menu-item index="/layout/index"><icon name="dashboard"></icon>首页</el-menu-item>
        <el-submenu index="user">
          <template slot="title">
            <icon name="user"></icon>用户
          </template>
          <el-menu-item index="/layout/user">用户管理</el-menu-item>
          <el-menu-item index="/layout/Blog">博客管理</el-menu-item>
<!--          <el-menu-item index="/layout/permission">权限管理</el-menu-item>-->
        </el-submenu>
<!--        <el-menu-item index="3"><i class="el-icon-setting"></i><span class="layout-text">导航三</span></el-menu-item>
        <el-submenu index="1">
          <template slot="title">
            <icon name="dashboard"></icon>导航一
          </template>
          <el-menu-item index="1-1">选项1</el-menu-item>
          <el-menu-item index="1-2">选项2</el-menu-item>
          <el-menu-item index="1-3">选项3</el-menu-item>
          <el-submenu index="1-4">
            <template slot="title">选项4</template>
            <el-menu-item index="1-4-1">选项1</el-menu-item>
          </el-submenu>
        </el-submenu>
        <el-menu-item index="2"><i class="el-icon-menu"></i><span class="layout-text">导航二</span></el-menu-item>
        <el-menu-item index="3"><i class="el-icon-setting"></i><span class="layout-text">导航三</span></el-menu-item>
        <el-submenu index="1">
          <template slot="title">
            <icon name="dashboard"></icon>导航一
          </template>
          <el-menu-item index="1-1">选项1</el-menu-item>
          <el-menu-item index="1-2">选项2</el-menu-item>
          <el-menu-item index="1-3">选项3</el-menu-item>
          <el-submenu index="1-4">
            <template slot="title">选项4</template>
            <el-menu-item index="1-4-1">选项1</el-menu-item>
          </el-submenu>
        </el-submenu>
        <el-menu-item index="2"><i class="el-icon-menu"></i><span class="layout-text">导航二</span></el-menu-item>
        <el-menu-item index="3"><i class="el-icon-setting"></i><span class="layout-text">导航三</span></el-menu-item>
        <el-submenu index="1">
          <template slot="title">
            <icon name="dashboard"></icon>导航一
          </template>
          <el-menu-item index="1-1">选项1</el-menu-item>
          <el-menu-item index="1-2">选项2</el-menu-item>
          <el-menu-item index="1-3">选项3</el-menu-item>
          <el-submenu index="1-4">
            <template slot="title">选项4</template>
            <el-menu-item index="1-4-1">选项1</el-menu-item>
          </el-submenu>
        </el-submenu>
        <el-menu-item index="2"><i class="el-icon-menu"></i><span class="layout-text">导航二</span></el-menu-item>
        <el-menu-item index="3"><i class="el-icon-setting"></i><span class="layout-text">导航三</span></el-menu-item>-->
      </div>
    </el-menu>
  </div>
</template>

<script>
  export default{
  }
</script>
<style lang="stylus" rel="stylesheet/stylus">
.navbar
  .el-menu
    border-radius 0
    .navbar-logo
      margin 15px auto
      width 90%
      height 30px
      font-weight bold
      font-size 25px
      letter-spacing 3px
      text-align center
      color #ffffff
      line-height 1
      background url("../../assets/img/navbar-logo.png") no-repeat center
      background-size 90% 30px
    .navbar-menu
      position fixed
      top 60px
      bottom 0
      left 0
      background-color #324157
      width 12.5%
      overflow-y auto
      &::-webkit-scrollbar
        width 0
    .fa-icon
      width auto
      height 18px
      margin-right 10px
</style>

<template>
    <el-container>
        <el-aside style="width: 200px;margin-top: 20px">
            <Switch></Switch>
            <SideMenu></SideMenu>
        </el-aside>
        <!-- <el-main>
          <books class="book-area"></books>
        </el-main> -->
    </el-container>
</template>

<script>
import SideMenu from './SideMenu'
export default {
  name: 'AppLibrary',
  components: {SideMenu}
}
</script>

<style scoped>
  .books-area {
      width: 990px;
      margin-left: auto;
      margin-right: auto;
  }
</style>

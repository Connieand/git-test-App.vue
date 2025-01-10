<template>
  <div id="app">
    <!-- 路由占位符 -->
    <!-- <keep-alive :include="['PlanProgramGenerate']"> -->
    <keep-alive :include="['PlanSchemeVerification']">
      <router-view></router-view>
    </keep-alive>
  </div>
</template>

<script>
export default {
  name: 'app',
}
</script>

<style>
.redWarning p {
  color: red;
  padding: 0;
  margin: 0;
}
</style>
//Git-TEST仅用于测试
//用于第二次测试
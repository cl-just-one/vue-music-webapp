<template>
  <div class="loading">
    <img width="24" height="24" src="./loading.gif" alt="加载动画">
    <p class="desc">{{title}}</p>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: '正在载入......'
    }
  }
}
</script>

<style lang="scss" scoped>
@import './loading.scss'
</style>

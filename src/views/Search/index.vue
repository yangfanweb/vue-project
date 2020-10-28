<template>
  <div>
      Search
      params参数:{{keyword}}
      <br><br>
      query参数:{{keyword1}}
  </div>
</template>

<script>
export default {
  name: 'search',
  props:['keyword1','keyword']
}
</script>

<style lang="less" scoped>

</style>

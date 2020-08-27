<template>
  <div v-if="!show" class="my-test1">
      <h1>this is my test1</h1>
      <el-button>Hello</el-button>
  </div>
</template>

<script>
export default {
    data(){
        return {
            show:false
        }
    }
}
</script>

<style lang="less">
.my-test1{
    h1{
        color:red;
    }
}
</style>
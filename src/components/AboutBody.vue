<template>
  <div>
    <div>关于我们的主体内容</div>
    <p>{{msg}}</p>
  </div>

</template>

<script>
    export default {
        name: "AboutBody",
        props:["msg"]
    }
</script>

<style scoped>
    div{
      text-align: center;
    }
</style>

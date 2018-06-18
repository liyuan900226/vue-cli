<template>
    <div>
      <h2>这是首页的主体部分</h2>
      <p>{{msg}}</p>
      <button>点击执行函数</button>
    </div>
</template>

<script>

    export default {
        name: "IndexBody",
        props:["msg"]
    }
</script>

<style scoped>
    h2{
      text-align: center;
    }
</style>

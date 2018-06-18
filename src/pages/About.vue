<template>
  <div>
    <Head></Head>
    <AboutBody></AboutBody>
    <AllFoot></AllFoot>
  </div>
</template>

<script>
  //引入子组件“头部”
  import Head from "../components/Head"
  import AboutBody from "../components/AboutBody"
  import AllFoot from "../components/AllFoot"
  export default {
    name: "index",
    components:{// 在components字段中，包含导入的子组件
      Head,AboutBody,AllFoot
    }
  }
</script>

<style scoped>

</style>

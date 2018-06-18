<template>
  <div>
    <Head></Head>
    <AllFoot></AllFoot>
  </div>

</template>

<script>
  //引入子组件“头部”
  import Head from "../components/Head"

  import AllFoot from "../components/AllFoot"
    export default {
        name: "Case",
      components:{// 在components字段中，包含导入的子组件
        Head,AllFoot
      }
    }
</script>

<style scoped>

</style>

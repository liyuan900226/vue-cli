<template>
    <div>
        <Head></Head>
        <!--------------传参时，v-bind：命名为啥必须和  传的参数名一致！！！！！！！！------------------->
        <IndexBody v-bind:msg="msg"></IndexBody>
        <p>{{cc}}</p>
        <AllFoot></AllFoot>
    </div>
</template>

<script>
    //引入子组件“头部”
    import Head from "../components/Head"
    import IndexBody from "../components/IndexBody"
    import AllFoot from "../components/AllFoot"
    export default {
        name: "index",
        components:{// 在components字段中，包含导入的子组件
            Head,IndexBody,AllFoot
        },
      data(){
          return {
            cc:"首页的数据",
            msg:"index传递到indexbody组件的数据"
          }
      }
    }
</script>

<style scoped>

</style>

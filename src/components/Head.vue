<template>
  <div>
    <ul>
      <li><router-link to="/">首页</router-link></li>
      <li><router-link to="/about">关于我们</router-link></li>
      <li>成功案例</li>
      <li>产品介绍</li>
      <li>联系我们</li>
    </ul>
  </div>
</template>

<script>
    export default {
      props:["current"],
      name: "Head"
    }
</script>

<style scoped>
  ul{
    overflow: hidden;
    list-style: none;
    padding: 0;
  }
  li{
    text-align: center;
    float: left;
  }
  li{width: 20%}
  li a{
    text-decoration: none;
    width: 100%;
    display: block;
  }
  li:hover a{
    color: red;
    background-color: #0d6aad;
  }
  li.active{
    background-color: #00a7d0;
  }
</style>

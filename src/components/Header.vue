<template>
    <div class="header">
      <router-link :to="{name:'root'}">
        <img src="../assets/cnodejs_light.svg" alt="">
      </router-link>
      <ul>
        <li>
          <router-link :to="{name:'root'}">
            首页
          </router-link>
        </li>
        <li><a href="https://cnodejs.org/getstart" target="view_window">新手入门</a></li>
        <li><a href="https://cnodejs.org/api" target="view_window">API</a></li>
        <li><a href="https://cnodejs.org/about" target="view_window">关于</a></li>

      </ul>
    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
 .header{
   background-color: #444;
   height: 50px;
 }
 img{
   max-width: 120px;
   margin-left: 50px;
   margin-top: 10px;
 }

  ul{
    list-style: none;
    float: right;
    margin: 4px;
  }

  li{
    display: inline-block;
    padding: 10px 15px;
  }

  a{
    text-decoration: none;
    color: #ccc;
    font-size: 14px;
    text-shadow: none;
  }
</style>

<template>
  <div class="footer">
    <ul>
      <li>
        <router-link to="/index">首页</router-link>
      </li>
      <li>
        <router-link to="/order">订单</router-link>
      </li>
      <li>
        <router-link to="/mine">我的</router-link>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  name: "navbar"
};
</script>
<style>
.footer{ position: absolute; width:100%;height:50px;line-height: 50px;bottom: 0px;left:0px;background: #ffffff;border-top: solid #dddddd 1px;padding-left:5%;padding-right: 5%; }
.footer ul{ width:100%;height:100%;overflow: hidden; }
.footer ul li{ width:33%;float: left;font-size: 16px;padding:0 3%;}
.footer ul li a{ color:#000;text-decoration: none;text-align: center; }
</style>



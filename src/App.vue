<template>
  <div id="body">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'Body'
}
</script>

<style>
#body {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

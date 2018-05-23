<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
html,body,div{
  height:100%;
}
body{
  background-image: url(./assets/Wallpaper.jpg);
  background-repeat:no-repeat;
　background-size: 2000px 2000px;
}
</style>

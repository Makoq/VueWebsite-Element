<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>
<script>
export default {
  name: 'app',
  data () {
    return {
    }
  }
}
</script>
<style lang="scss">
body{
  height: 100%;
  margin: 0px;
  padding: 0px;
}
#app{
height: 100%;
min-height: 100%;
}
</style>

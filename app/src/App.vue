<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="stylus">
body
  background-color #212121

#app
  font-family 'Raleway', 'sans-serif';
  font-weight 300
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color white

h2
  font-weight 200
</style>

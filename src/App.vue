<template>
  <div id="app">
    <a v-bind:class="{active: isActive,error:hasError}">検索エンジン</a>
  </div>
</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      isActive: true,
      hasError:false
    }
  }
}
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.active{
  color: #fff;
  background-color: red;
}
</style>

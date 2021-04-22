<template>
  <div id="app">
    <a v-bind:style="styleObject">検索エンジン</a>
  </div>
</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      styleObject: {
        fontSize: '12px',
        color: 'red'
      }
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

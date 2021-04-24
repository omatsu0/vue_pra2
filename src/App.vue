<template>
  <div id="app">
    <p v-if="stock_number > 0">販売中です</p>
    <p v-else>在庫切れのため販売していません</p>
  </div>
</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      stock_number: 1
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

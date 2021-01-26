<template>
  <div id="app">
    <h1>teste</h1>
    
    <router-link to="/">Home</router-link>
    <router-link to="/products">Proutos</router-link>
    <router-link to="/sales">Vendas</router-link>
    <router-view></router-view>

   
  
  </div>
</template>

<script>
export default {
  name: 'app'
  
}
</script>

<style>

</style>

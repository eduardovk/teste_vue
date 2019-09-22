<template>
  <div id="app">
    <ProdutosExemplo></ProdutosExemplo>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import ProdutosExemplo from './components/Produtos'

export default {
  name: 'App',
  components: {
    HelloWorld,
    ProdutosExemplo
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

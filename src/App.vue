<template>
  <div id="app">
    <Button texto="Carlos" color="#2F2F33" :onClick="handleAlert" />
    <Button texto="Carlos" :onClick="handleAlert2"  />
  </div>
</template>


<script>
import Button from './components/Button.vue'

export default {
  name: 'App',
  components: {
    Button
  },
  methods: {
    handleAlert() {
      alert("fui pressionado")
      return 'fui';
    },
    handleAlert2() {
      alert("fui pressionado 2")
      return 'fui';
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

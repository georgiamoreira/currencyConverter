 <!-- sempre esse template no inicio -->
<template>
 <!-- sempre essa div no inicio -->
  <div id="app">
    <Conversor moeda-a="USD" moeda-b="BRL" />
 <!-- moedaA = moeda-a  -->

  </div>
</template>

<script>
import Conversor from "./components/Conversor.vue";
export default {
  name: 'App',
  components: {
    Conversor
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

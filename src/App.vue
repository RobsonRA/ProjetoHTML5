<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/mve.png">
    <HelloWorld msg="Tostines é mais gostosa porque é fresquina"/>
    <BotaoBonito></BotaoBonito>
    <Botao2Lindo></Botao2Lindo>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import BotaoBonito from './components/BotaoLaranja.vue'
import Botao2Lindo from './components/Botao2lLindo.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    BotaoBonito,
    Botao2Lindo
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

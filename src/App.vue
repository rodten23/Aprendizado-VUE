<template>
  <!--Aqui seria a área do HTML-->
  <div id="app"> <!--A <div></div> é o componente raiz (root) e todo mundo tem que ficar dentro dela.-->
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Bem-Vindo a minha página do Vue.js"/>
    <h2>Olá, Mundo! Vamos muito além do JavaScript puro?</h2>
    <h3>▼ Clique no botão abaixo e descubra outros projetos ▼</h3>
    <BotaoBonito></BotaoBonito>
  </div>
</template>

<script>
// Aqui seria a área do JavaScript
import HelloWorld from './components/HelloWorld.vue'
import BotaoBonito from './components/Botao.vue' //Além de importar Botao aqui, depois por ele no export default abaixo
                                                 //e também por ele na página (dentro da <div>), tem que montar o
                                                 // "export default" dentro dele próprio (Botao.vue)

export default {
  name: 'App',
  components: {
    HelloWorld, BotaoBonito
  }
}
</script>

<style>
/* Aqui seria a área do CSS*/
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

body {
  background-color: #c0fdf2;
}
</style>

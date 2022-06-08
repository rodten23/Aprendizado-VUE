<template>
    <button>Vamos voar!?</button>
</template>

<script>
export default {
  name: 'BotaoBonito',
  props: {
    msg: String
  }
}
</script>

<style scoped>
button {
  color: #42b983;
  background: #35495e;
  width: 120px;
  height: 27px;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  font-weight: 900;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
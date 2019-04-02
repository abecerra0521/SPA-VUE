<template>
  <div id="app">
    <div class="container">
      <img src="./assets/logo.png">
      <h1>{{ msg }}</h1>
      <button class="btn btn-primary">Enviar</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      msg: 'Hello world!!'
    }
  }
}
</script>

<style lang="css">
  @import './css/main.css';
</style>

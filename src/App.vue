<template>
  <div id="app">
    <topbar></topbar>
    <hero></hero>
    <div class="container">
      <div class="row">
        <div class="offset-by-two eight columns">
          <testes></testes>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Topbar from './components/Topbar'
import Hero from './components/Hero'
import Testes from './components/Testes'

export default {
  name: 'app',
  components: {
    Topbar,
    Hero,
    Testes
  }
}
</script>
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>

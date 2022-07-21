<template>
  <div id="app">
    <Title/>
    <Jumbo/>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Jumbo from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    Title,
    Jumbo,
  }
}
</script>

<style lang="scss">
  body{
    font-family: sans-serif;
    font-size: 20px;
  }
</style>
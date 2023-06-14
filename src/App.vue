<template>
  <div>
    <AComponent />
    <BComponent />
  </div>
</template>

<script>
import AComponent from './components/AComponent.vue'
import BComponent from './components/BComponent.vue'

export default {
  name: 'App',
  components: {
    AComponent,
    BComponent
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

<template>
  <hello-world msg="Welcome to Your Vue.js App" />
  <single-component />
  <parent-component />
  <click-event />
</template>

<script>
import ClickEvent from './components/ClickEvent.vue'
import HelloWorld from './components/HelloWorld.vue'
import SingleComponent from './components/SingleComponent.vue'
import ParentComponent from './components/ParentComponent.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    SingleComponent,
    ParentComponent,
    ClickEvent
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



<template>
  <div id="app">
    <TodoApp />
  </div>
</template>

<script>
import TodoApp from './components/TodoApp.vue';

export default {
  name: 'App',
  components: {
    TodoApp
  }
}
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  text-align: center;
  background-color: #29c7dc;
  width: auto;
  min-height: 100vh; 
  overflow:hidden;
}
todo-app {
  height: auto; 
}
</style>


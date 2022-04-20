
<template>
<div class="app">
  <img class="logo" alt="Vue logo" src="./assets/logo.png">
  
<h1 class="h1">Simon the GAME</h1>
<p>Запомни и открой все зеленные клетки</p>

<BoardBoard />
</div>
</template>

<script>
import BoardBoard from './components/BoardBoard';
  export default {
    name: 'App',
    components: {
      BoardBoard,

    }
  }
</script>

<style scoped>
.app {
    font-family: Helvetica, sans-serif;
    text-align: center;
    margin-top: 40px;
}
.logo {
  width: 100px;
}
</style>
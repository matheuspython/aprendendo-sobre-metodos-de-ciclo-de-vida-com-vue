<template>
  <TheMain />
</template>

<script>
import TheMain from './components/TheMain.vue';

export default {
  name: 'App',
  components: {
    TheMain
}
}
</script>

<style>
  *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
  html,body{
    font-family: sans-serif;
  }

#app {
  width: 100%;
}
</style>

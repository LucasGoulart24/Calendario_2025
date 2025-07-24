<template>
    <Calendario/>
</template>

<script>
import Calendario from './components/Calendario.vue';

export default {
  name: 'App',
  components: {
    Calendario
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body{
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  background-color: lightblue;
}
</style>
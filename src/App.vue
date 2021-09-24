<template>
  <img alt="UOH logo" src="./assets/fake_uoh.png" style="width:250px">
  <Timetable msg="あほんだらー"/>
</template>

<script>
import Timetable from './components/Timetable.vue'

export default {
  name: 'App',
  components: {
    Timetable
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

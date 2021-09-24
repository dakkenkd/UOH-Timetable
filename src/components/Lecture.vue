<template>
  <td><a :href="URL">{{name}}</a></td>
</template>

<script>
export default {
  name: 'Lecture',
  props: {
    URL: String,
    name: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

<template>
  <td><a :href="URL" :style="isTaken">{{name}}</a></td>
</template>

<script>
export default {
  name: 'Lecture',
  props: {
    URL: String,
    name: String,
    flag: String
  },
  computed: {
    isTaken() {
      if (this.flag == "true") {
        return "color: red"
      } else {
        return "color: blue"
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

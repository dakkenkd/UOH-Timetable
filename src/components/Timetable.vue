<template>
  <div class="timetable">
    <table>
      <thead>
        <th class="num"></th>
        <th class="day">Monday</th>
        <th class="day">Tuesday</th>
        <th class="day">Wednesday</th>
        <th class="day">Thursday</th>
        <th class="day">Friday</th>
      </thead>

      <tbody>
        <td>1</td>
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
      </tbody>

      <tbody>
        <td>2</td>
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
      </tbody>

      <tbody>
        <td>3</td>
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
      </tbody>

      <tbody>
        <td>4</td>
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
      </tbody>

      <tbody>
        <td>5</td>
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
        <Lecture URL="https://twitter.com/home?lang=ja" name="Twitter概論" />
      </tbody>
    </table>
  </div>
</template>

<script>
import Lecture from './Lecture.vue'

export default {
  name: 'Timetable',
  components: {
    Lecture
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

table {
  margin: 0 auto;
  margin-top: 50px;
}

.day {
  width: 120px;
}

.num {
  width: 30px
}

td {
  height: 80px;
}

table, td {
  border: 1px solid #333;
}

thead, tfoot {
  background-color: #333;
  color: #fff;
}
</style>

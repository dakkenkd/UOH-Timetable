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
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
        <Lecture flag=true URL="https://twitter.com/home?lang=ja" name="English for Specific Purposes Ⅱ" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/153060.pdf" name="最適化理論" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
      </tbody>

      <tbody>
        <td>2</td>
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/151240.pdf" name="情報セキュリティ" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/151280.pdf" name="計算理論" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/152060.pdf" name="政策データ分析" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="山本ゼミ" />
      </tbody>

      <tbody>
        <td>3</td>
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/153080.pdf" name="グラフ理論" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/151300.pdf" name="情報メディア論" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="玉置ゼミ" />
      </tbody>

      <tbody>
        <td>4</td>
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/151200.pdf" name="システム管理" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/151260.pdf" name="ソフトウェア開発論" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="川嶋ゼミ" />
      </tbody>

      <tbody>
        <td>5</td>
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/151220.pdf" name="コンピュータネットワーク" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/undergraduate/index.html" name="なし" />
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

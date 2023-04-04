<template>
  <div class="timetable">
    <table>
      <thead>
        <th class="num"></th>
        <th class="day">Monda<a href="https://www.amazon.co.jp/" style="color: white">y</a></th>
        <th class="day">Tuesday</th>
        <th class="day">Wednesday</th>
        <th class="day">Thursday</th>
        <th class="day">Friday</th>
      </thead>

      <tbody>
        <td>1</td>
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMS000101.pdf" name="システムセキュリティ特論" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
      </tbody>

      <tbody>
        <td>2</td>
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMD000401.pdf" name="機械学習特論" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMD000301.pdf" name="情報マネジメント特論" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMD000701.pdf" name="オペレーションズリサーチ特論" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMB000602.pdf" name="計算科学演習" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMB000501.pdf" name="計算科学概論" />
      </tbody>

      <tbody>
        <td>3</td>
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMB000102.pdf" name="情報科学概論" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMS000401.pdf" name="ネットワークセキュリティ特論" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
      </tbody>

      <tbody>
        <td>4</td>
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMB000902.pdf" name="プログラミング演習" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMB000202.pdf" name="情報科学演習" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMB000801.pdf" name="情報セキュリティ科学概論" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
      </tbody>

      <tbody>
        <td>5</td>
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
        <Lecture flag=true URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/pdf/ISMB000301.pdf" name="データ科学概論" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
        <Lecture flag=false URL="https://www.u-hyogo.ac.jp/campuslife/syllabus/graduate/in-jyouhou/index.html" name="なし" />
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

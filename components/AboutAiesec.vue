<template>
    <div class="About-Aiesec">
        <h2>About AIESEC</h2>

        <p>AIESEC（アイセック）とは、世界126の国と地域に支部を持ち、<br>
        約70000人のメンバーが所属している、世界最大級の学生団体です。</p>

        <p>海外インターンシップへの参加、そして運営を通して、<br>
        世界を前進させることのできる次世代のリーダーを生み出すことを目指して活動しています。</p>

        <p>興味のある方はぜひ一度説明会やイベントにお越しください！</p>

    <div class="Button">
        <Button />
    </div>
    </div>
</template>

<script>
import Button from '~/components/Button.vue'

export default {
  components: {
      Button
  }
}
</script>

<style scoped lang="scss">
.About-Aiesec {
    width: 100%;
    height: 100vh;
    background-color:#ffffff;
    text-align: center;

    h2 {
        color: black;
        font-style: italic;
        font-weight: bold;
        font-size: 38px;
        letter-spacing: 0.1em;
        padding-bottom: 50px;
        padding-top: 200px;
    }

    p {
        color: black;
        font-size: 15px;
        letter-spacing: 0.3em;
        line-height: 2;
        margin: 1.2em 0;
    }
}

.Button {
    margin: 55px;
    margin-left: auto;
    margin-right: auto;
}
</style>
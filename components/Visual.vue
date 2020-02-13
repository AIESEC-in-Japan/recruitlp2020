<template>
  <div class="visual-container">
    <h1>
      世界を変えるのは、
      <br />誰だっていい。
    </h1>

    <h2>
      ステートメント
      <br />ステートメント
      <br />ステートメント
    </h2>

    <h2 class="subtitle">
      別に誰が変えたっていいんだよ
      <br />キミかもしれないんだよ
    </h2>

    <h2>うんぬんかんぬんぬん。</h2>
  </div>
</template>

<style scoped lang = "scss">
.visual-container {
  width: 100%;
  height: 100vh;
  background-image: url('../assets/images/visual-background.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  flex-direction: column;
  align-items: center;
  align-content: space-between;
  justify-content: center;
  text-align: center;

  h1 {
    color: #fff;
    font-style: italic;
    font-size: 30px;
    padding: 30px 0;
  }

  h2 {
    color: #fff;
    font-size: 18px;
    padding: 30px 0;

    .subtitle {
      font-style: italic;
    }
  }
}
</style>
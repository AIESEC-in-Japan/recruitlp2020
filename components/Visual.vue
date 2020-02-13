<template>
  <div class="visual-container">
    <h1>
      世界を変えるのは、
      <br />誰だっていい。
    </h1>

    <p>
      ステートメント
      <br />ステートメント
      <br />ステートメント
    </p>

    <p class="message-sub">
      別に誰が変えたっていいんだよ
      <br />キミかもしれないんだよ
    </p>

    <p>うんぬんかんぬんぬん。</p>
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
    padding: 30px 0;
    font-size: 30px;
  }

  p {
    color: #fff;
    font-style: italic;
    font-size: 18px;
    padding: 30px 0;
    &.message-sub {
      font-style: italic;
    }
  }
}
</style>
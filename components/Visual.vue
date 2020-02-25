<template>
  <div class="visual-container">
    <h1>
      世界を変えるのは、
    </h1>

<!---    <p>
      もしかしたら君かもしれないし、
      <br />もしかしたらあの子かもしれないし、
      <br />もしかしたらみんなかもしれない
    </p>
		--->
    <p class="message-sub">
      別に誰が変えたっていいんだよ
      <br />キミかもしれないんだよ
    </p>

    <p>
			一緒に世界を良くする仲間になることを、
			<br />考えてみてもらえませんか。
		</p>
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
  letter-spacing: 0.3em;
	line-height: 32px;

  h1 {
    color: #fff;
    font-style: italic;
    padding: 40px 0;
    font-size: 30px;
  }

  p {
    color: #fff;
    font-style: italic;
    font-size: 18px;
    padding: 10px 0;
    &.message-sub {
      font-style: italic;
    }
  }
}
</style>

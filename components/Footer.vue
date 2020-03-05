<template>
  <footer class="footer">
    <div class="footer-bottom">
      <div class="copy-right-text">
        <p>
          <small>Copyright &copy; 2020 AIESEC in Japan All rights reserved.</small>
        </p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
.footer {
  background-color: #000;
  color: #fff;
  height: 2em;

  .footer-bottom {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;

    .copy-right-text {
      p {
        small {
          color: #fff;
          font-size: 12px;
          line-height: 12px;
        }
      }
    }
  }
}
</style>
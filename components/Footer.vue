<template>
  <!-- footer start -->
  <footer class="footer">
    <div class="footer-bottom">
      <div class="copy-right-text">
        <p>Copyright &copy; 2020 AIESEC in Japan All rights reserved.</p>
      </div>
    </div>
  </footer>
  <!--/ footer end  -->
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
.footer {
  background-color: #000;
  color: #fff;
  height: 5em;

  .footer-bottom {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    padding: 2em;

    .copy-right-text {
      p {
        color: #fff;
      }
    }
  }
}
</style>
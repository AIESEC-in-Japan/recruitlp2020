<template>
  <!-- footer start -->
  <footer class="footer">
    <div class="footer-top">
      <div class="footer-top-logo">
        <a src="#">
          <img src="../assets/images/logo.png" />
        </a>
      </div>
      <div>
        <ul class="footer-menu">
          <li class="footer-menu-items" src="#">あいうえお</li>
          <li class="footer-menu-items" src="#">かきくけこ</li>
          <li class="footer-menu-items" src="#">さしすせそ</li>
          <li class="footer-menu-items" src="#">たちつてと</li>
          <li class="footer-menu-items" src="#">なにぬねの</li>
        </ul>
      </div>
    </div>
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

  .footer-top {
    display: flex;
    flex-flow: row wrap;
    padding: 30px;

    .footer-top-logo {
      height: 2em;
      width: 15em;
      margin-right: 5em;
      margin-left: 5em;

      img {
        height: 100%;
        width: 100%;
      }
    }
    .footer-menu {
      display: flex;
      list-style: none;
      margin-right: 3em;
      margin-left: 3em;
      .footer-menu-items {
        padding: 0.6em;
        margin: 0.1em;
      }
    }
  }

  .footer-bottom {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    padding-bottom: 30px;

    .copy-right-text {
      p {
        color: #fff;
      }
    }
  }
}
</style>
<template>
  <header class="header-container">
    <nav>
      <ul>
        <li>
          <a href="#about">about.</a>
        </li>
        <li>
          <a href="#internships">interships.</a>
        </li>
        <li>
          <a href="#activities">activities.</a>
        </li>
        <li>
          <a href="/join">join.</a>
        </li>
        <li>
          <a href="/contact">contact.</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped lang="scss">
.header-container {
  position: fixed;
  top: 0;
  background-color: black;
  width: 100%;
  height: 80px;
  line-height: 80px;

  display: flex;
  justify-content: flex-end;
  margin: 0 auto;
  padding: 0px 5%;

  ul {
    display: flex;
  }
  li {
    margin-left: 50px;
    list-style-type: none;
    letter-spacing: 7px;
    display: inline-block;
  }
  a {
    color: #fff;
    font-weight: bold;
    text-decoration: none;
    font-size: 15px;
    font-style: italic;
  }
  a:hover {
    opacity: 0.7;
  }
  img {
    height: 25px;
  }
}
</style>

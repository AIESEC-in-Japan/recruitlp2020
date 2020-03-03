<template>
  <a v-bind:href="link" class="Button">{{ text }}}</a>
</template>

<script>
export default {
  name: 'LinkedButton',
  props: {
    link: String,
    text: String
  }
}
</script>

<style scoped lang="scss">
.Button {
  display: block;
  padding-top: 15px;
  padding-bottom: 15px;
  width: 350px;
  font-size: 14px;
  background-color: white;
  color: #00aeef;
  -webkit-transition: all 0.3s ease;
  -moz-transition: all 0.3s ease;
  -o-transition: all 0.3s ease;
  transition: all 0.3s ease;
  border: solid 2px #00aeef;
  border-radius: 15px;
  text-align: center;
  text-decoration: none;

  &:hover {
    background-color: #00aeef;
    color: white;
  }
}
</style>

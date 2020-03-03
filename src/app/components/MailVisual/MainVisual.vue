<template>
  <div class="main-visual">
    <p>世界を変えるのは、</p>
    <LinkedButton
      v-bind:text="this.entry.entryText"
      v-bind:link="this.entry.entryLink"
    />
  </div>
</template>

<script>
import LinkedButton from '../common/atoms/LinkedButton'

export default {
  components: { LinkedButton },
  data() {
    return {
      entry: {
        entryLink: 'http://www.aiesec.jp/',
        entryText: '新歓説明会にいってみる'
      }
    }
  }
}
</script>

<style scoped lang="scss">
.main-visual {
  width: 100%;
  height: 100vh;
  background-color: black;
  display: flex;
  align-items: center;
  justify-content: center;

  p {
    color: white;
    font-style: italic;
    font-weight: bold;
    font-size: 30px;
    letter-spacing: 0.2em;
  }
}
</style>

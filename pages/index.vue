<template>
  <div class="wrapper">
    <MainVisual />
    <Visual />
    <AboutAiesec />
  </div>
</template>

<script>
import MainVisual from '~/components/MainVisual.vue'
import Visual from '~/components/Visual.vue'
import Button from '~/components/Button.vue'
import AboutAiesec from '~/components/AboutAiesec.vue'

export default {
  components: {
    MainVisual,
    Visual,
    Button,
    AboutAiesec,
  }
}
</script>

<style></style>

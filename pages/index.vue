<template>
  <div class="wrapper">
    <MainVisual />
    <Visual />
  <div class="Button">
    <Button/>
  <div class="AboutAIESEC">
    <AboutAIESEC/>
  </div>
  </div>
  </div>
</template>

<script>
import MainVisual from '~/components/MainVisual.vue'
import Visual from '~/components/Visual.vue'
import Button from '~/components/Button.vue'
import AboutAIESEC from '~/components/AboutAIESEC.vue'

export default {
  components: {
    MainVisual,
    Visual,
    Button,
    AboutAIESEC,
  }
}
</script>

<style></style>

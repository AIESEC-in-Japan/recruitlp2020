<template>
  <div class="wrapper">
    <MainVisual />
    <Visual />
    <div id="about">
      <AboutAiesec />
    </div>
    
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
  },
  mounted() {
    this.$nextTick(() => {
      this.$nuxt.$loading.start()
      setTimeout(() => this.$nuxt.$loading.finish(), 3000)
    })
  }
}
</script>

<style></style>

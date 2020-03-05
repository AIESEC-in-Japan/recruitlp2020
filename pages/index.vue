<template>
  <div class="wrapper">
    <MainVisual />
    <Visual />
    <Footer />
  </div>
</template>

<script>
import MainVisual from '~/components/MainVisual.vue'
import Visual from '~/components/Visual.vue'
import Button from '~/components/Button.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    MainVisual,
    Visual,
    Button,
    Footer
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

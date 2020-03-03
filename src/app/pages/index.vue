<template>
  <div class="wrapper">
    <MainVisual />
    <Visual />
  </div>
</template>

<script>
import MainVisual from '~/components/MainVisual.vue'
import Visual from '~/components/Visual.vue'
import Button from '~/components/LinkedButton.vue'

export default {
  components: {
    MainVisual,
    Visual,
    Button
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

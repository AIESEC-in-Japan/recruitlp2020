<template>
  <div class="wrapper">
  <a class="button">
    <MainVisual />
    <Visual />
    <Button />
  </a>
  </div>
</template>
<script>
import MainVisual from '~/components/MainVisual.vue'
import Visual from '~/components/Visual.vue'
import Button from '~/components/Button.vue'

export default {
  components: {
    MainVisual,
    Visual,
    Button,
  },
  mounted () {
    this.$nextTick(() => {
      this.$nuxt.$loading.start()

      setTimeout(() => this.$nuxt.$loading.finish(), 500)
    })
  },
}
</script>

<style>
</style>

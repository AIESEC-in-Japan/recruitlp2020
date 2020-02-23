<template>
  <div class="wrapper">
    <MainVisual />
    <Visual />
  <div class="Button">
    <Button/>
  </div>
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
  }
}
</script>

<style></style>

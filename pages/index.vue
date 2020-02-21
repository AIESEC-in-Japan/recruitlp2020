<template>
  <div class="wrapper">
    <MainVisual />
    <Visual />
     <a class="Button">
    <Button/>
  </a>
  </div>
</template>

<script>
import MainVisual from '~/components/MainVisual.vue'
import Visual from '~/components/Visual.vue'
import Button from '~/Button/Visual.vue'


export default {
  components: {
    MainVisual,
    Visual,
    Button
  }
}
</script>

<style></style>

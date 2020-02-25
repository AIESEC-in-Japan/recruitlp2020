<template>
  <div v-show="loading" class="loading">
    <div class="anim" ref="lavContainer"></div>
  </div>
</template>

<script>
import loading from "@/assets/animation/loading.json";

export default {
  data: () => ({
    loading: false,
    options: {
      animationData,
      loop: false,
      autoplay: false,
      rendererSettings: ""
    }
  }),
  mounted() {
    this.anim = lottie.loadAnimation({
      container: this.$refs.lavContainer,
      renderer: "svg",
      loop: this.options.loop !== false,
      autoplay: this.options.autoplay !== false,
      animationData: this.options.animationData,
      rendererSettings: this.options.rendererSettings
    });
  },
  methods: {
    start() {
      this.anim.play();
      console.log("debug loading start")
      this.loading = true;
    },
    finish() {
      this.anim.stop();
      this.loading = false;
      console.log("debug loading finish")
    }
  }
}
</script>

<style scoped>
.loading {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: white;
  text-align: center;
  padding-top: 200px;
  font-size: 30px;
  font-family: sans-serif;
  z-index: 9999;
}

.anim {
  height: 100px;
  margin: 0 auto;
  overflow: hidden;
  width: 100px;
}
</style>
<template>
  <div v-show="loading" class="loading">
    <div class="anim" ref="lavContainer"></div>
  </div>
</template>

<script>
import * as animationData from "@/assets/animation/loading.json";
import lottie from "lottie-web";

export default {
    data () {
      return {
        loading: false,
        options: {
          animationData,
          loop: false,
          autoplay: false,
          rendererSettings: ""
        },
      }
    },

  mounted() {
    console.log(this.options.animationData.default)
    this.anim = lottie.loadAnimation({
      container: this.$refs.lavContainer,
      renderer: "svg",
      loop: true,
      autoplay: this.options.autoplay !== false,
      animationData: this.options.animationData.default,
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
      console.log("debug loading finish")
      this.loading = false;
    }
  }
}
</script>

<style scoped>
.loading {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: black;
  font-size: 30px;
  font-family: sans-serif;
  z-index: 9999;
}

.anim {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  margin: auto;
  height: 30%;
  overflow: hidden;
  width: 30%;
}
</style>
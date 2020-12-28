<template>
  <div class="screen">
    <ParticlesJS />
  </div>
</template>

<script>
import ParticlesJS from "./ParticlesJS"

export default {
  name: "HelloWorld",
  components: {
    ParticlesJS
  },
  data() {
    return {
      
    }
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.screen {
  height: 100vh;
  width: 100vw;
  background-color: black;
  position: absolute;
  top: 0;
  left: 0;
  z-index: -1;
}
</style>

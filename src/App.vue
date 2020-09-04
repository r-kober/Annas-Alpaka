<template>
  <div id="app">
    <alpaka />
    <a href="https://de.vecteezy.com/gratis-vektor/alpaka"
      >Alpaka Vektoren von Vecteezy</a
    >
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Alpaka from "@/components/Alpaka.vue";

export default defineComponent({
  name: "App",
  components: {
    Alpaka
  }
});
</script>

<style lang="less">
#app {
  margin-top: 60px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 100vh;
}
</style>

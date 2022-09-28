<template>
  <Spline :scene="scene" />
</template>

<script>
import Spline from "spline-vue/v2";

export default {
  components: { Spline },
  data() {
    return {
      scene: "https://prod.spline.design/6Wq1Q7YGyM-iab9i/scene.splinecode",
    };
  },
};
</script>
<style>
body {
  margin: 0;
  height: 100vh;
}
</style>

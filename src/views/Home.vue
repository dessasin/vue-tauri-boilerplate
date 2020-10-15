<template>
  <div class="home">
    <div class="logos">
      <img alt="Taur logo" src="../assets/tauri.png" />
      <p>+</p>
      <img alt="Vue logo" src="../assets/logo.png" />
    </div>
    <HelloWorld msg="🚀🚀 Welcome to Your Tauri Powered Vue.js App 🚀🚀" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>
<style >
img {
  max-width: 100px;
}
.logos {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>

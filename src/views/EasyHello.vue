<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloEasyUIDemo />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloEasyUIDemo from "@/components/HelloEasyUI.vue";

export default {
  name: "easyUiHome",
  components: {
    HelloEasyUIDemo
  }
};
</script>

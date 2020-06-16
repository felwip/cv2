<template>
  <div class="home">
    <h1>Felix</h1>
    <img alt="Vue logo" src="../assets/logo.png" />
    <Tech />
  </div>
</template>

<script>
import Tech from "@/components/Tech.vue";

export default {
  name: "Home",
  components: {
    Tech
  }
};
</script>

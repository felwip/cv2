<template>
  <div class="home">
    <h1>Welcome</h1>
    <Bar />
    <Tech />
  </div>
</template>

<script>
import Tech from "@/components/Tech.vue";
import Bar from "@/components/Icon-Bar.vue";

export default {
  name: "Home",
  components: {
    Tech,
    Bar
  }
};
</script>

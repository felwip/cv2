<template>
  <div>
    <div class="icon-bar">
      <img src="../../src/assets/pictures/portrait.jpeg" />
      <img src="../../src/assets/pictures/CodeCampLeipzig.jpg" />
      <img src="../../src/assets/pictures/bike.jpg" />
      <img src="../../src/assets/pictures/rocketbean.jpg" />
      <img src="../../src/assets/pictures/amateur.jpg" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.icon-bar {
  display: flex;
  justify-content: space-around;
}

img {
  width: 100px;
  height: 100px;
  object-fit: cover;
  border-radius: 50%;
  transition: transform 0.3s;
}

img:hover {
  transform: scale(1.5);
}
</style>

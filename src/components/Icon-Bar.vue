<template>
  <div>
    <div class="icon-bar">
      <img src="../../src/assets/pictures/portrait.jpeg" alt=" " />
      <img src="../../src/assets/pictures/CodeCampLeipzig.jpg" alt=" " />
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
  flex-direction: column;
  align-items: center;
  text-decoration: line-through;
}

img {
  width: 8rem;
  height: 8rem;
  overflow: hidden;
  object-fit: cover;
  border: 0.2px solid var(--dark-beige);
  border-radius: 50%;
  transition: transform 0.3s;
  margin: 2rem;
}

img:hover {
  transform: scale(1.5);
}
</style>

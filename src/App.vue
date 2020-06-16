<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">CV</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0,300;0,700;1,300&family=Raleway:ital,wght@0,400;0,700;1,400&display=swap");

body {
  margin: 0;
  background-color: var(--primary-white);
}

#app {
  font-family: "Open Sans Condensed", sans-serif;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--primary-green);
}

:root {
  --primary-blue: #4d6d6b;
  --primary-green: #3d4c3d;
  --light-beige: #cfdbc5;
  --dark-beige: #a4ae93;
  --primary-white: #f9f6e8;
}

h1,
h2,
h3,
h4 {
  font-family: "Raleway", sans-serif;
  -webkit-font-smoothing: antialiased;
}

#nav {
  padding: 30px;
  letter-spacing: 3px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

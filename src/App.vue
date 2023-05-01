<template>
  <router-view />
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600&display=swap");

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: "Montserrat", sans-serif;
}

body {
  background: linear-gradient(to bottom right, #ff8be0, #ffe364);
  color: #1a2250;
  height: 100vh;
}
a {
  color: #6189ff;
  font-weight: bold;
  text-decoration: none;
}
button {
  appearance: none;
  border: none;
  cursor: pointer;
  background: linear-gradient(to bottom right, #8bcdff, #6487ff);
  font-size: 1.125rem;
  color: #fff;
  padding: 0.5rem 1rem;
  border-radius: 0.5rem;
}
</style>

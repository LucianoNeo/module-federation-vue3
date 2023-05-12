<template>
  <div class="container">
    <div class="top-container">
      <h4 class="header">Header do container (app principal)</h4>
    </div>
    <footer-element/>
  </div>
</template>

<script setup></script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  border: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.top-container {
  background-color: #ff6600;
  width: 100%;
  height: 100px;
}
.header {
  color: #ffffff;
  padding-top: 20px;
}
</style>

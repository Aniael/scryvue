<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'HYPE', 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.full-height{
  min-height: 100vh;
}

</style>

<style>
@font-face {
  font-family: "hype";
  src: local("HYPE"),   url(./fonts/HYPE.ttf) format("truetype");}
</style>

<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  height: 100vh;
}
html,
body,
p {
  margin: 0;
  padding: 0;
}
p {
  text-align: left;
}
</style>

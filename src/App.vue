<template>
  <div id="app">
    <div id="nav"></div>
    <router-view />
  </div>
</template>

<script>
import Home from "@/components/Home.vue";
import Projects from "@/components/Projects.vue";
export default {
  components: {
    Home,
    Projects
  }
};
</script>

<style>
#app {
  font-family: "Montserrat", sans-serif;
  background-color: #233142;
  color: rgb(241, 217, 191);
}
</style>

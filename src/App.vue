<template>
  <div id="app">
    <div id="nav">
      <router-view />
    </div>
  </div>
</template>

<script>
import Home from "@/views/Home.vue";
import Projects from "@/views/Projects.vue";

export default {
  name: "app",

  components: {
    Home,
    Projects
  }
};
</script>

<style>
#app {
  font-family: "Nunito";
  background-color: #233142;
  color: rgb(241, 217, 191);
}
</style>

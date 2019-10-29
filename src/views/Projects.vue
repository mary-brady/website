<template>
  <div class="projects container-fluid">
    <p>hello, world!</p>
  </div>
</template>

<script>
// @ is an alias to /src
import Home from "@/views/Home.vue";

export default {
  name: "Projects",
  components: {
    Home
  }
};
</script>
<style >
.projects {
  min-height: 100vh;
}
</style>

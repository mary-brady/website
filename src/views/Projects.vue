<template>
  <div class="projects container-fluid">
    <div class="row">
      <div class="col-md-10 offset-md-1 top-container">
        <router-link :to="{name: 'home'}">
          <i class="fas fa-arrow-left back-icon" alt="Home"></i>
        </router-link>
      </div>
    </div>
    <div class="row margin-top: 40px;">
      <div class="col-md-10 offset-md-1">
        <h1 class="borderb">
          <p class="bigger-font">Projects</p>
        </h1>
      </div>
    </div>
    <div class="row h35">
      <div class="col-md-10 offset-md-1">
        <div class="card text-white bg-dark mb-3" style="max-width: 540px;">
          <div class="row no-gutters">
            <div class="col-md-4">
              <img src="../assets/4RiversProject.png" class="card-img" alt="..." />
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h3 class="card-title project-border">4RiversInspections</h3>
                <p class="card-text">Small business website relating to home inspections.</p>
                <ul>
                  <li>
                    <p class="card-text">
                      <small>Vuejs</small>
                    </p>
                  </li>
                  <li>
                    <p class="card-text">
                      <small>Vuetify</small>
                    </p>
                  </li>
                  <li>
                    <p class="card-text">
                      <small>cPanel</small>
                    </p>
                  </li>
                </ul>
                <a
                  :href="'http://www.4riversinspections.com' "
                  class="btn btn-light"
                  targer="_blank"
                >View</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
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

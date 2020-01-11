<template>
  <div class="projects container-fluid">
    <div class="row">
      <div class="col-md-10 offset-md-1">
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
      <div class="col-md-5 offset-md-1">
        <div class="card text-white bg-dark mb-3" style="max-width: 540px;">
          <div class="row no-gutters">
            <div class="col-md-4">
              <img src="../assets/4RiversProject.png" class="card-img" alt="4Rivers Inspections" />
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
                <div class="row">
                  <div class="col-6">
                    <a
                      :href="'http://www.4riversinspections.com' "
                      class="btn btn-light btn-sm"
                      target="_blank"
                    >View</a>
                  </div>
                  <div class="col-6">
                    <a
                      :href="'https://github.com/mary-brady/4riversinspections' "
                      class="btn btn-light btn-sm"
                      target="_blank"
                    >Source</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-5">
        <div class="card text-white bg-dark mb-3" style="max-width: 540px;">
          <div class="row no-gutters">
            <div class="col-md-4">
              <img src="../assets/YOFT.png" class="card-img img-fluid" alt="YOFT" />
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h3 class="card-title project-border">YOFT</h3>
                <p
                  class="card-text"
                >Boise CodeWorks capstone. Group effort fitness tracker with daily challenges, workout builder, and progress charts.</p>
                <div class="row">
                  <div class="col-4">
                    <ul>
                      <li>
                        <p class="card-text">
                          <small>Vuejs</small>
                        </p>
                      </li>
                      <li>
                        <p class="card-text">
                          <small>Node.js</small>
                        </p>
                      </li>
                    </ul>
                  </div>
                  <div class="col-4">
                    <ul>
                      <li>
                        <p class="card-text">
                          <small>ChartJS</small>
                        </p>
                      </li>
                      <li>
                        <p class="card-text">
                          <small>Heroku</small>
                        </p>
                      </li>
                    </ul>
                  </div>
                </div>
                <div class="row">
                  <div class="col-6">
                    <a
                      :href="'https://yoft.herokuapp.com/' "
                      class="btn btn-light btn-sm"
                      target="_blank"
                    >View</a>
                  </div>
                  <div class="col-6">
                    <a
                      :href="'https://github.com/mary-brady/capstone' "
                      class="btn btn-light btn-sm"
                      target="_blank"
                    >Source</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row h35">
      <div class="col-md-5 offset-md-1">
        <div class="card text-white bg-dark mb-3" style="max-width: 540px;">
          <div class="row no-gutters">
            <div class="col-md-4">
              <img src="../assets/Keepr.png" class="card-img" alt="Keepr" />
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h3 class="card-title project-border">Keepr</h3>
                <p class="card-text">Final Boise CodeWorks project - Pinterest clone.</p>
                <div class="row">
                  <div class="col-4">
                    <ul>
                      <li>
                        <p class="card-text">
                          <small>Vuejs</small>
                        </p>
                      </li>
                      <li>
                        <p class="card-text">
                          <small>C#</small>
                        </p>
                      </li>
                    </ul>
                  </div>
                  <div class="col-4">
                    <ul>
                      <li>
                        <p class="card-text">
                          <small>MySQL</small>
                        </p>
                      </li>
                      <li>
                        <p class="card-text">
                          <small>Heroku</small>
                        </p>
                      </li>
                    </ul>
                  </div>
                </div>
                <div class="row">
                  <div class="col-6">
                    <a
                      :href="'https://not-pinterest.herokuapp.com/' "
                      class="btn btn-light btn-sm"
                      target="_blank"
                    >View</a>
                  </div>
                  <div class="col-6">
                    <a
                      :href="'https://github.com/mary-brady/keepr' "
                      class="btn btn-light btn-sm"
                      target="_blank"
                    >Source</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- <div class="col-md-5">
        <div class="card text-white bg-dark mb-3" style="max-width: 540px;">
          <div class="row no-gutters">
            <div class="col-md-4">
              <img src="../assets/YOFT.png" class="card-img img-fluid" alt="..." />
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h3 class="card-title project-border">YOFT</h3>
                <p
                  class="card-text"
                >Boise CodeWorks capstone. Group effort fitness tracker with daily challenges, workout builder, and progress charts.</p>
                <ul>
                  <li>
                    <p class="card-text">
                      <small>Vuejs</small>
                    </p>
                  </li>
                  <li>
                    <p class="card-text">
                      <small>Node.js</small>
                    </p>
                  </li>
                  <li>
                    <p class="card-text">
                      <small>ChartJS</small>
                    </p>
                  </li>
                  <li>
                    <p class="card-text">
                      <small>Heroku</small>
                    </p>
                  </li>
                </ul>
                <div class="row">
                  <div class="col-6">
                    <a
                      :href="'https://yoft.herokuapp.com/' "
                      class="btn btn-light btn-sm"
                      target="_blank"
                    >View</a>
                  </div>
                  <div class="col-6">
                    <a
                      :href="'https://github.com/mary-brady/capstone' "
                      class="btn btn-light btn-sm"
                      target="_blank"
                    >Source</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>-->
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
.card-img {
  width: 100%;
  height: 100%;
}
</style>

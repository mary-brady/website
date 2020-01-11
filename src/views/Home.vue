<template>
  <div class="home container-fluid">
    <div class="row h35 about">
      <div class="col-lg-12">
        <div class="col-md-10 offset-md-1">
          <h1 class="borderb">
            <p class="bigger-font">Mary Brady</p>
          </h1>
          <p class="text-right mb-0">SEO.</p>
          <p class="text-right mb-0">Full stack developer.</p>
          <p class="text-right">Snack enthusiast.</p>
        </div>
      </div>
    </div>
    <div class="row align-items-center justify-content-center h35">
      <div class="col-lg-2 lines">
        <div class="vl"></div>
      </div>
      <div class="col-lg-2 text-center">
        <a href="https://github.com/mary-brady" target="_blank">
          <i class="fab fa-github"></i>
        </a>
      </div>
      <div class="col-lg-2 text-center">
        <a href="https://www.linkedin.com/in/mary-c-brady" target="_blank" alt="LinkedIn">
          <i class="fab fa-linkedin"></i>
        </a>
      </div>
      <div class="col-lg-2 text-center">
        <router-link :to="{name: 'projects'}">
          <i class="far fa-folder-open" alt="Projects"></i>
        </router-link>
      </div>
      <div class="col-lg-2 text-center">
        <a
          :href="'https://docs.google.com/document/d/11RYU3RdR-2qUoyu6gcXXs7587_IuBXhcUbjIaOXv-6Q/edit?usp=sharing' "
          target="_blank"
        >
          <i class="far fa-id-card"></i>
        </a>
      </div>
      <div class="col-lg-2">
        <div class="vl"></div>
      </div>
    </div>
    <!-- <div class="row">
      <div class="col-lg-12">
        <hr />
      </div>
    </div>-->
    <div class="row contact">
      <div class="col-lg-10 offset-lg-1">
        <p class="no-margin borderc">mbrady.js@gmail.com</p>
        <p class="no-margin">775.340.2418</p>
        <!-- <hr class="contact-line" /> -->
      </div>
    </div>
    <div class="row contact text-left">
      <div class="col-lg-10 offset-lg-1"></div>
    </div>
    <!-- <div class="row">
      <div class="col-lg-12">
        <hr />
      </div>
    </div>-->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Projects from "@/views/Projects.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    Projects
  }
};
</script>
<style >
.h35 {
  min-height: 35vh;
  justify-content: center;
  align-items: center;
}

.no-margin {
  margin-bottom: 0;
}

.contact-line {
  max-width: 10%;
  margin-top: 0;
  margin-bottom: 0;
  height: 1px;
}
.contact {
  min-height: 10vh;
  align-items: center;
  color: rgb(235, 247, 253);
  /* justify-content: center;
  text-align: center; */
}
.borderb {
  border-bottom: 2px solid rgb(83, 99, 114);
  display: inline-block;
  width: inherit;
  color: rgb(83, 99, 114);
}
.borderc {
  border-bottom: 2px solid rgb(83, 99, 114);
  display: inline-block;
  width: 40%;
  color: rgb(235, 247, 253);
}
.project-border {
  border-bottom: 2px solid rgb(83, 99, 114);
  /* display: inline-block; */
  /* width: inherit; */
  color: whitesmoke;
}

/* .top-container {
  border-bottom: 2px solid rgb(83, 99, 114);
  width: 90vw;
} */

/* testing autopush to git */

hr {
  display: block;
  height: 1px;
  border-top: 2px solid rgb(83, 99, 114);
  padding: 0;
}
a,
i {
  color: rgb(235, 247, 253);
  font-size: 40px;
}

.back-icon {
  color: rgb(235, 247, 253);
  font-size: 30px;
}

/* .social {
  align-items: center;
  text-align: center;
} */
.bigger-font {
  font-size: larger;
  font-family: "Nunito";
}

p {
  font-size: small;
  color: rgb(235, 247, 253);
}

.about {
  background-color: #233142;
  color: white;
  font-family: "Nunito";
  display: flex;
}

.vl {
  border-left: 2px solid rgb(83, 99, 114);
  height: 10vh;
}

.lines {
  display: flex;
  justify-content: flex-end;
  color: rgb(83, 99, 114);
}

.home {
  min-height: 100vh;
}
</style>

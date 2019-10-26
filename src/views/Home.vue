<template>
  <div class="home container-fluid">
    <div class="row h55 about">
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
    <div class="row align-items-center social">
      <div class="col-lg-12">
        <hr />
      </div>
      <!-- <div class="col-lg-3"></div> -->
      <div class="col-lg-2 offset-md-3">
        <a href="https://github.com/mary-brady" target="_blank">
          <i class="fab fa-github"></i>
        </a>
      </div>
      <div class="col-lg-2">
        <a href="https://www.linkedin.com/in/mary-c-brady" target="_blank" alt="LinkedIn">
          <i class="fab fa-linkedin"></i>
        </a>
      </div>
      <div class="col-lg-2">
        <router-link :to="{name: 'Projects'}">
          <i class="far fa-folder-open" alt="Projects"></i>
        </router-link>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-12">
        <hr />
      </div>
    </div>
    <div class="row contact">
      <div class="col-lg-12 contact-font">
        <p class="no-margin">mbrady.js@gmail.com</p>
        <hr class="contact-line" />
        <p>775.340.2418</p>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-12">
        <hr />
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Projects from "@/components/Projects.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    Projects
  }
};
</script>
<style >
.h55 {
  min-height: 35vh;
  justify-content: center;
  align-items: center;
}

.bigger-font {
  font-size: medium;
}

.no-margin {
  margin-bottom: 0;
}

.contact-line {
  max-width: 60%;
  margin-top: 0;
  margin-bottom: 0;
  height: 1px;
}
.contact {
  min-height: 10vh;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.borderb {
  border-bottom: 2px solid white;
  display: inline-block;
  width: inherit;
  color: white;
}
.borderc {
  border-bottom: 2px solid white;
  display: inline-block;
  width: 12%;
  color: white;
}
hr {
  display: block;
  height: 1px;
  border-top: 2px solid white;
  padding: 0;
}
a,
i {
  color: white;
  font-size: 40px;
}

.social {
  align-items: center;
  text-align: center;
}
.bigger-font {
  font-size: larger;
  font-family: "Montserrat", sans-serif;
}

p {
  font-size: small;
}

.about {
  background-color: #233142;
  color: white;
  font-family: "Montserrat", sans-serif;
  display: flex;
}
</style>

<template>
  <div class="home container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <div class="col-md-10 offset-md-1">
          <h1 class="borderb">
            <b>Mary Brady</b>
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
        <a href="https://www.linkedin.com/in/mary-c-brady" target="_blank">
          <i class="fab fa-linkedin"></i>
        </a>
      </div>
      <div class="col-lg-2">
        <i class="far fa-folder-open"></i>
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

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
<style>
.borderb {
  border-bottom: 2px solid rgb(224, 224, 224);
  display: inline-block;
  width: inherit;
  color: rgb(224, 224, 224);
}
hr {
  display: block;
  height: 1px;
  border-top: 3px solid rgb(224, 224, 224);
  padding: 0;
}
a,
i {
  color: rgb(224, 224, 224);
  font-size: 45px;
}

.social {
  align-items: center;
  text-align: center;
}
p {
  font-size: medium;
}
</style>

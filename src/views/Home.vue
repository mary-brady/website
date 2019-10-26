<template>
  <div class="home container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <div class="col-md-10 offset-col-2">
          <h1 class="borderb">
            <b>Mary Brady</b>
          </h1>
          <p class="text-right mb-0">SEO.</p>
          <p class="text-right mb-0">Full stack developer.</p>
          <p class="text-right">Snack enthusiast.</p>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-12">
        <hr />
      </div>
      <div class="col-lg-4">
        <i class="fab fa-github"></i>
      </div>
      <div class="col-lg-4">
        <i class="fab fa-linkedin"></i>
      </div>
      <div class="col-lg-4">
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
<style class="scoped">
i {
  font-size: 10vm;
}
</style>

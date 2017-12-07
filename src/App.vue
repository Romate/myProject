<template>
  <div id="app">
  <oneTitle></oneTitle>
  <div id="main-container" class="container">
    <div class="row frontpage">
      <div class="col-md-8">
        <div class="fp-one">
          <div id="carousel-one" class="carousel slide">
            <banner></banner>
            <list></list>
          </div>
        </div>
      </div>
      <test></test>
    </div>
  </div>
    <!--img src="./assets/logo.png">
    <router-view/-->
  </div>
</template>

<script>
import oneTitle from './components/oneTitle.vue';
import banner from './components/banner.vue';
import list from './components/list.vue';
import test from './components/test.vue';
export default {
    components: {
    oneTitle,
    banner,
    list,
    test,

  }
}
</script>

<style>

</style>

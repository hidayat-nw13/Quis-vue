<template>
  <div id="app">
    <navbarCmp></navbarCmp>
    <breadcrumbCmp></breadcrumbCmp>
    <galeryCmp></galeryCmp>
    <sliderCmp></sliderCmp>
    <footerCmp></footerCmp>
    <CopyrightCmp></CopyrightCmp>

  </div>
</template>


<script>
import navbarCmp from "./components/navbarCmp.vue";
import breadcrumbCmp from "./components/breadcrumbCmp.vue";
import galeryCmp from "./components/galeryCmp.vue";
import sliderCmp from "./components/sliderCmp.vue";
import footerCmp from "./components/footerCmp.vue";
import CopyrightCmp from "./components/copyrightCmp.vue";


export default {
  name: "App",
  components: {
    navbarCmp,
    breadcrumbCmp,
    galeryCmp,
    sliderCmp,
    footerCmp,
    CopyrightCmp
  },
}
</script>

<style>

</style>
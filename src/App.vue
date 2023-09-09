<template>
  <div id="app">
    <HeaderComponent />
    <HomeComponent />
    <AboutUs />
    <!-- <OurServices /> -->
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import HomeComponent from './components/HomeComponent.vue';
import AboutUs from './components/AboutUs.vue';
// import OurServices from './components/OurServices.vue';


export default {
  components: {
    HeaderComponent,
    HomeComponent,
    AboutUs,
    // OurServices,
  },
};
</script>
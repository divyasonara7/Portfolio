<template>
  <Banner />
  <HomeAbout />
  <Testimonials />
  <HomeHireMe />
</template>
<script>
import Banner from "../components/Banner.vue";
import HomeAbout from "../components/HomeAbout.vue";
import Testimonials from "../components/Testimonials.vue";
import HomeHireMe from "../components/HomeHireMe.vue";
export default {
  components: {
    Banner,
    HomeAbout,
    Testimonials,
    HomeHireMe,
  },
};
</script>

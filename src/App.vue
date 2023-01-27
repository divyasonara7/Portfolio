<template>
  <NavBar />
  <Banner />
  <HomeAbout />
  <HomeSkillSet />
  <HomeProjects />
  <!-- <HomeResumeSection /> -->

  <Testimonials />
  <!-- <HomeVideoPopUp /> -->
  <HomeHireMe />
  <HomeFooter />
</template>
<script>
import NavBar from "./components/NavBar.vue";
import Banner from "./components/Banner.vue";
import HomeAbout from "./components/HomeAbout.vue";
// import HomeResumeSection from './components/HomeResumeSection.vue';
import HomeProjects from "./components/HomeProjects.vue";
import HomeSkillSet from "./components/HomeSkillSet.vue";
import Testimonials from "./components/Testimonials.vue";
// import HomeVideoPopUp from './components/HomeVideoPopUp.vue';
import HomeHireMe from "./components/HomeHireMe.vue";
import HomeFooter from "./components/Footer.vue";
export default {
  components: {
    NavBar,
    Banner,
    HomeAbout,
    // HomeResumeSection,
    HomeProjects,
    HomeSkillSet,
    Testimonials,
    // HomeVideoPopUp,
    HomeHireMe,
    HomeFooter,
  },
  setup() {},
};
</script>

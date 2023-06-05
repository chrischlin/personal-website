<script>
import Intro from "../components/Intro.vue";
import MySkills from "../components/MySkills.vue";
import Projects from "../components/Projects.vue";
import Footer from "../components/Footer.vue";

export default {
  components: { Intro, MySkills, Projects, Footer },
};
</script>

<template>
  <Intro />
  <MySkills />
  <Projects />
  <Footer />
</template>

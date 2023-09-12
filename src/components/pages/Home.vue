<template>
  <NavBar />
  <AboutView />
  <ExperienceView />
  <EducationView />
  <ContatoView />
  <FooterView />
</template>

<script>
import NavBar from "../NavBar.vue";
import AboutView from "../About.vue";
import FooterView from "../Footer.vue";
import ExperienceView from "../Experience.vue";
import EducationView from "../Education.vue";
import ContatoView from "../Contato.vue";

export default {
  name: "HomePage",
  components: {
    NavBar,
    AboutView,
    ExperienceView,
    FooterView,
    EducationView,
    ContatoView,
  },
};
</script>

<style scoped></style>

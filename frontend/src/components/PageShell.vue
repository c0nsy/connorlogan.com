<template>
  <div class="one">
    <NavBar />
    <div class="section-wrapper">
      <ProfileHeader />
      <AboutSection />
      <WorkSection />
      <ProjectsSection />
    </div>
  </div>
</template>
<script>
import NavBar from "./nav/NavBar.vue";
import ProfileHeader from "../modules/profile-header/ProfileHeader.vue";
import AboutSection from "../modules/about/AboutSection.vue";
import WorkSection from "../modules/work/WorkSection.vue";
import ProjectsSection from "../modules/projects/ProjectsSection.vue";
export default {
  name: "PageShell",
  components: {
    NavBar,
    ProfileHeader,
    AboutSection,
    WorkSection,
    ProjectsSection,
  },
};
</script>
<style scoped src="./styles/page-shell-styles.css"></style>

<template>
  <div>
    <HeaderSection />
    <HeroSection />
    <AboutSection />
    <SkillsSection />
    <ProjectsSection />
    <ContactSection />
  </div>
</template>

<script>
// Importing components from their respective paths
import HeaderSection from '~/components/HeaderSection.vue';
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import SkillsSection from '~/components/SkillsSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';

export default {
  components: {
    HeaderSection,
    HeroSection,
    AboutSection,
    SkillsSection,
    ProjectsSection,
    ContactSection,
  }
}
</script>

<style scoped>
/* Scoped styles for Index.vue */
/* Add your global styles here if needed */
</style>

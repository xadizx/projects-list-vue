<template>
  <div :key="project.id" v-for="project in projects">
    <ProjectCard :project="project" />
  </div>
</template>

<script>
import ProjectCard from "./ProjectCard.vue";

export default {
  name: "Projects",
  components: {
    ProjectCard,
  },
  props: {
    projects: Array,
  },
};
</script>

<style scoped></style>

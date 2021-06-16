<template>
  <div class="card">
    <h2>{{ project.name }}</h2>
    <p>{{ project.description }}</p>
  </div>
</template>

<script>
export default {
  name: "ProjectCard",
  props: {
    project: Object,
  },
};
</script>

<style scoped>
/* .card {
} */
</style>

<template>
  <About />
  <Projects :projects="projects" />
</template>

<script>
import About from "./components/About.vue";
import Projects from "./components/Procjets.vue";

export default {
  name: "App",
  components: {
    About,
    Projects,
  },

  data() {
    return {
      projects: [],
    };
  },

  created() {
    this.projects = [
      {
        id: 1,
        name: "Nazwa 1",
        description: "Desc 1",
      },
      {
        id: 2,
        name: "Nazwa 2",
        description: "Desc 2",
      },
    ];
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap");

body {
  background-color: rgb(208, 208, 208);
}
</style>

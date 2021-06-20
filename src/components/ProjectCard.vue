<template>
  <!-- md:bg-transparent-->
  <div
    class="mx-auto p-2 w-90 max-w-5xl sm:w-full sm:p-4 h-auto rounded-2xl mt-5"
  >
    <h2 class="text-3xl font-bold text-center mb-5">
      {{ project.name }}
    </h2>
    <div class="flex flex-col md:flex-row gap-5">
      <div class="self-center flex flex-col items-center">
        <img :src="'/img/' + project.img" class="rounded-xl filter h-64 mb-5" />
        <a
          v-if="project.url !== null"
          v-bind:href="`https://` + project.url"
          target="_blank"
          class="url"
          >{{ project.url }}</a
        >

        <a
          v-if="project.github !== null"
          v-bind:href="project.github"
          class="github"
          target="_blank"
          >Github</a
        >
        <a
          v-if="project.gallery !== null"
          v-bind:href="project.gallery"
          class="github"
          target="_blank"
          >Galeria</a
        >
      </div>
      <div class="flex sm:flex-1 flex-col">
        <span class="text-lg line-clamp-3 text-justify justify-self-center">
          {{ project.description }}
        </span>
      </div>
    </div>
    <hr />
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
hr {
  border: 0;
  border-top: 1px solid rgba(0, 0, 0, 0.1);
  margin-top: 3rem;
}

.url {
  color: #8884ff;
  font-weight: bold;
}

.github {
  font-weight: bold;
  color: #1c2826;
}
</style>

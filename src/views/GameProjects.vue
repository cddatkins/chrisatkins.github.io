<template>
  <div class="projects">
    <h1>Game Projects</h1>

    <div style="margin-bottom: 30px;">
      The following are games I've made or heavily contributed to.
    </div>

    <ProjectsList v-bind:projects="projects" />

  </div>
</template>

<script lang="ts">
import Vue from "vue";
import ProjectsList from "@/components/ProjectsList.vue";
import gameProjectsData from "@/data/GameProjectsData.ts";

export default Vue.extend({
  name: "GameProjects",
  components: {
    ProjectsList,
  },
  data: function () {
    return {
      projects: gameProjectsData,
    };
  },
});
</script>

<style scoped>
.projects {
  width: 50%;
  margin: 0 auto;
}
.tech-stack {
  font-style: italic;
}
</style>

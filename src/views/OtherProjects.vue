<template>
  <div class="projects">  
    <h1>Other Projects</h1>

    <div style="margin-bottom: 30px;">
      And here are some other projects I've made or heavily contributed to.
    </div>
    <ProjectsList v-bind:projects="projects" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import ProjectsList from "@/components/ProjectsList.vue";
import otherProjectsData from "@/data/OtherProjectsData.ts";

export default Vue.extend({
  name: "OtherProjects",
  components: {
    ProjectsList,
  },
  data: function () {
    return {
      projects: otherProjectsData,
    };
  },
});
</script>

<style scoped>
.projects {
  width: 50%;
  margin: 0 auto;
  
}
</style>
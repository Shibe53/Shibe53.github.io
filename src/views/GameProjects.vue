<template>
  <div>
    <h1>Game Dev</h1>

    <div style="margin-bottom: 30px;">
      The following are games and game-related project I have worked on.
    </div>

    <ProjectsList v-bind:projects="projects" />

    <div style="margin-top: 20px;">
      More on <a target="_blank" href="https://shibe53.itch.io/">my itch.io</a>.
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import ProjectsList from "../components/ProjectsList.vue";
import gameProjectsData from "../data/GameProjectsData.ts";

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

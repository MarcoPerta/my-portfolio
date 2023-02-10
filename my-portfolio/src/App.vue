
<template>
  <div>
    <HomeComp />

    <AboutComp />

    <SkillsComp />
  </div>
</template>

<script setup>
import HomeComp from "./components/HomeComp.vue";
import AboutComp from "./components/AboutComp.vue";
import SkillsComp from "./components/SkillsComp.vue";
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&display=swap");

* {
  font-family: "Space Mono", monospace;
}
</style>

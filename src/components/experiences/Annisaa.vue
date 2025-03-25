<script setup lang="ts">
import LayoutExperience from './LayoutExperience.vue';

const datas = [
  "Developing front end website architecture",
  "Designing user interactions on web pages",
  "Developing back-end website applications",
  "Creating servers and databases for functionality",
  "Meeting both technical and consumer needs"
]
</script>
<template>
  <LayoutExperience>
    <div class="flex justify-between items-center">
      <div>
        <h1 class="text-2xl font-bold">FullStack Developer</h1>
        <h5 class="text-slate-400 text-sm">An-Nisaa Hospital</h5>
      </div>
      <h5 class="text-sm">Aug 2023 - Nov 2023</h5>
    </div>
    <p>
      Developing an information communication technology system that processes and integrates the entire workflow of
      hospital services in the form of a coordinated network, encompassing coordination, reporting, and administrative
      procedures to obtain precise and accurate information. It is part of the Health Information System.
    </p>
    <ul class="list-disc pl-5">
      <li v-for="data in datas" :key="data">{{ data }}</li>
    </ul>
  </LayoutExperience>
</template>

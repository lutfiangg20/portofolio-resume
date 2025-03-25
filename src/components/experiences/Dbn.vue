<script setup lang="ts">
import LayoutExperience from './LayoutExperience.vue';

const datas = [
  "Work with development teams and product managers to ideate software solutions",
  "Design client-side and server-side architecture",
  "Build the front-end of applications through appealing visual design",
  "Develop and manage well-functioning databases and applications",
  "Troubleshoot, debug, upgrade software and test software to ensure responsiveness and efficiency",
  "Build features and applications with a mobile responsive design",
  "Write effective APIs, Write technical documentation"
]

</script>

<template>
  <LayoutExperience>
    <div class="flex justify-between items-center">
      <div>
        <h1 class="text-2xl font-bold">FullStack Developer</h1>
        <h5 class="text-slate-400 text-sm">PT. Data Buana Nusantara - Arre Tech</h5>
      </div>
      <h5 class="text-sm">Jan 2023 - Present</h5>
    </div>
    <p>
      Website development, maintenance, and more. Provide solutions to help company or business grow. Our clients are
      governments, corporations, overseas and multinational companies.
    </p>
    <ul class="list-disc pl-5">
      <li v-for="data in datas" :key="data">{{ data }}</li>
    </ul>
  </LayoutExperience>
</template>

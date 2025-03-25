<script setup lang="ts">
import LayoutExperience from './LayoutExperience.vue';
const datas = [
  "Drafting website designs, including layout and menu structures",
  "Monitoring and maintaining local government websites: changing templates, updating plugins, adding menus, etc.",
  "Implementing SEO (Search Engine Optimization) on local government websites",
  "Providing support to other agencies through technical consultations, training/orientation sessions, and assisting in website management"
]
</script>
<template>
  <LayoutExperience>
    <div class="flex justify-between items-center">
      <div>
        <h1 class="text-2xl font-bold">Frontend Developer</h1>
        <h5 class="text-slate-400 text-sm">The Department of Communication, Informatics, and Statistics</h5>
      </div>
      <h5 class="text-sm">Jan 2022 - Dec 2022</h5>
    </div>
    <p>
      The Department of Communication, Informatics, and Statistics is tasked with assisting the mayor in carrying out
      government affairs in the fields of Communication and Informatics, Statistics, and cryptographic matters within
      the authority of the local government, as well as providing support duties.
    </p>
    <ul class="list-disc pl-5">
      <li v-for="data in datas" :key="data">{{ data }}</li>
    </ul>
  </LayoutExperience>
</template>

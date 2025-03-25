<script setup lang="ts">
import Annisaa from './experiences/Annisaa.vue';
import Dbn from './experiences/Dbn.vue';
import Kominfo from './experiences/Kominfo.vue';



</script>
<template>
  <div id="experiences" class="flex flex-col gap-10 bg-slate-800 py-20 px-5">
    <h1 class="text-5xl font-bold text-center">Work Experience</h1>
    <Dbn />
    <Annisaa />
    <Kominfo />
  </div>
</template>

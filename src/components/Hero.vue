<script setup lang="ts">
import { User } from 'lucide-vue-next';


</script>
<template>
  <div class="flex justify-around items-center bg-slate-800 py-36 px-80">
    <div class="space-y-4  w-full">
      <h1 class="capitalize text-6xl font-bold">lutfi angga hendrawan</h1>
      <h2 class="text-slate-400 text-xl">Fullstack Developer with expertise in React, Vue, Laravel, and go</h2>
      <div class="flex gap-2">
        <button class="bg-blue-500 hover:bg-blue-600 rounded-md text-black p-2 text-sm">Contact Me</button>
        <button class="bg-slate-900 hover:bg-slate-800 rounded-md p-2 text-sm">View Projects</button>
      </div>
    </div>
    <div class="h-full">
      <div class=" w-[300px] h-[300px] rounded-full relative bg-linear-to-b from-blue-600 to-slate-800 from-5%">
        <div
          class="flex justify-center items-center bg-slate-800 w-[290px] h-[290px] rounded-full absolute bottom-1 right-[5px]">
          <User class="opacity-30" :size="100" />
        </div>
      </div>
    </div>
  </div>
</template>

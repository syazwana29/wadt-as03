<script setup lang="ts">
import { defineExpose } from "vue";
import profile from "./assets/profile.jpeg";

defineExpose({ profile });
</script>

<template>
  <div class="min-h-screen flex flex-col items-center justify-center lg:justify-start lg:items-start">
    <img :src="profile" class="w-80 h-80 rounded-full absolute ml-12 mt-0" />
    <p  class="text-2xl font-bold absolute ml-20 mt-80">DAYANGKU SYAZWANA</p>
  

<div class="flex flex-col items-center justify-center w-full text-center">
  <div>
    <h2 class="text-2xl text-black font-bold mb-16 ml-96" >
      Dayangku Syazwana Pengiran Haji Ismail Kairuluddin, 22FTT1515
    </h2>
    <p class="text-xl ml-96 mb-28">
      I am currently studying in Politeknik Brunei, taking level 5 Diploma in
      Web Development. Devoted to volleyball and loves creating and designing as
      a way to show my creativity. Likes playing video games to explore virtual
      worlds and losing themselves in the colorful worlds of anime and manga.
    </p>
  </div>

  <div class="ml-64">
    <p class="font-bold">CONTACT</p>
    <p>22FTT1515@student.pb.edu.bn</p>
    <p>+673 xxxxxxx</p>
    <p>www.syazwana.io</p>
  </div>
</div>
</div>
</template>

<style scoped>

</style>
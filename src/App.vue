<script setup lang="ts">
import { defineExpose } from "vue";
import profile from "./assets/profile.jpeg";

defineExpose({ profile });
</script>

<template>
  <div>
    <img :src="profile" class="w-80 h-80 rounded-full absolute ml-12 mt-16" />
    <p>DAYANGKU SYAZWANA</p>
  </div>

  <div>
    <h2>
      Dayangku Syazwana Pengiran Haji Ismail Kairuluddin, 22FTT1515
    </h2>
    <p>
      I am currently studying in Politeknik Brunei, taking level 5 Diploma in
      Web Development. Devoted to volleyball and loves creating and designing as
      a way to show my creativity. Likes playing video games to explore virtual
      worlds and losing themselves in the colorful worlds of anime and manga.
    </p>
  </div>

  <div>
    <p>CONTACT</p>
    <p>22FTT1515@student.pb.edu.bn</p>
    <p>+673 xxxxxxx</p>
    <p>www.syazwana.io</p>
  </div>
</template>

<style scoped>

/* .name {
  font-size: 25px;
  font-weight: bold;
  position: absolute;
  left: 95px;
  top: 450px;
  color: #000;
} */

/* .header {
  font-size: 25px;
  font-weight: bold;
  color: #000;
  margin-bottom: 60px;
  margin-left: 400px;
} */

/* .description { text-xl ml-400 mb-90
  font-size: 20px;
  color: #000;
  margin-left: 400px;
  margin-bottom: 90px;
} */

/* .contact-details {
  margin-left: 350px;
} */
</style>

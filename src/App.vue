<script setup lang="ts">
import { defineExpose } from "vue";
import profile from "./assets/profile.jpeg";

defineExpose({ profile });
</script>

<template>
  <div>
    <img class="profile-image" :src="profile" />
    <p class="name">DAYANGKU SYAZWANA</p>
  </div>

  <div>
    <h2 class="header">
      Dayangku Syazwana Pengiran Haji Ismail Kairuluddin, 22FTT1515
    </h2>
    <p class="description">
      I am currently studying in Politeknik Brunei, taking level 5 Diploma in
      Web Development. Devoted to volleyball and loves creating and designing as
      a way to show my creativity. Likes playing video games to explore virtual
      worlds and losing themselves in the colorful worlds of anime and manga.
    </p>
  </div>

  <div>
    <p style="font-weight: bold; margin-left: 120px">CONTACT</p>
  </div>
</template>

<style scoped>
.profile-image {
  border-radius: 50%;
  position: absolute;
  left: 50px;
  top: 65px;
  width: 350px;
  height: 350px;
}

.name {
  font-size: 25px;
  font-weight: bold;
  position: absolute;
  left: 95px;
  top: 450px;
  color: #000;
}

.header {
  font-size: 25px;
  font-weight: bold;
  color: #000;
  margin-bottom: 60px;
  margin-left: 400px;
}

.description {
  font-size: 20px;
  color: #000;
  margin-left: 400px;
  margin-bottom: 90px;
}
</style>

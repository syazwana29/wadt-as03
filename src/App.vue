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

  <div></div>
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
  left: 90px;
  top: 450px;
  color: #000;
}
</style>

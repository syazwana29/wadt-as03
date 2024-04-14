<script setup lang="ts">
import { defineExpose } from "vue";
import profile from "./assets/profile.jpeg";

defineExpose({ profile });
</script>

<template>
  <div>
    <img :src="profile" />
  </div>
</template>

<style scoped></style>

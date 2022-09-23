<script setup>
import Calendar from "primevue/calendar";
import { ref } from "vue";
const value = ref(new Date());
</script>

<template>
  <Calendar v-model="value" :readonly="true" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>

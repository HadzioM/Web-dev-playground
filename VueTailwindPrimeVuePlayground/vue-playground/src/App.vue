<script setup lang="ts">
import Button from 'primevue/button';
import SelectButton from 'primevue/selectbutton';
import { ref } from 'vue';

const value = ref('One-Way');
const options = ref(['One-Way', 'Return']);
</script>

<template>
  <div>
    <SelectButton v-model="value" :options="options" />
  </div>
</template>

<style scoped></style>

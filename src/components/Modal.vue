<script setup lang="ts">
import { ref } from 'vue';
type PropsModal =
  | {
      variant: 'no-title';
    }
  | {
      variant: 'title';
      title: string;
    };
const props = defineProps<PropsModal>();

const count = ref(0);
</script>

<template>
  <div v-if="props."
</template>

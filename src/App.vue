<template>
  <ThemeSwitcher />
  <div class="card flex justify-center">
    <Menu :model="items" />
  </div>
</template>

<script setup>
import { ref } from 'vue';

const items = ref([
  { label: 'Add', icon: 'pi pi-plus' },
  { label: 'Search', icon: 'pi pi-search' },
]);
</script>

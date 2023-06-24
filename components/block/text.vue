<script setup>
const props = defineProps({
  block: Object,
});
</script>

<template>
  <p :class="block.classes">
    {{ block.content }}
  </p>
</template>

<style></style>

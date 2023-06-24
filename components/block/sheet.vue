<script setup>
const props = defineProps({
  block: Object,
});

const getComponent = {
  row: resolveComponent('Row'),
  text: resolveComponent('Text'),
};
</script>

<template>
  <div :class="block.classes">
    <component
      v-for="innerBlock in block.blocks"
      :is="getComponent[innerBlock.name]"
      :block="innerBlock"
    ></component>
  </div>
</template>

<style></style>

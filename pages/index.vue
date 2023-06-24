<script setup>
const getComponent = {
  row: resolveComponent('Row'),
};

const blocksList = {
  blocks: [
    {
      name: 'row',
      blocks: [
        {
          name: 'col',
        },
        {
          name: 'col',
        },
      ],
    },
    {
      name: 'row',
      blocks: [],
    },
  ],
};
</script>

<template>
  <h1>Home</h1>

  <component
    v-for="block in blocksList.blocks"
    :is="getComponent[block.name]"
    :block="block"
  ></component>
</template>

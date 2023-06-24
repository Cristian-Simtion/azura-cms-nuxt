<script setup>
const getComponent = {
  row: resolveComponent('Row'),
  col: resolveComponent('Col'),
};

const blocksList = {
  blocks: [
    {
      name: 'row',
      blocks: [
        {
          name: 'col',
          classes: ['xs-2'],
        },
        {
          name: 'col',
          classes: ['xs-2'],
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

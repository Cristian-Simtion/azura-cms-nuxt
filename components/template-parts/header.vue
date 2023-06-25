<script>
export default {
  data() {
    return {
      isToggled: false,
    };
  },
  methods: {
    toggleClass() {
      this.isToggled = !this.isToggled;
    },
  },
};
</script>

<template>
  <ul class="list-simtion bg-neutral-90">
    <li :class="{ 'simtion-active': isToggled }">
      <NuxtLink to="/">Home</NuxtLink>
    </li>
    <li><NuxtLink to="/blog/blog-list">Blog list</NuxtLink></li>
    <li><NuxtLink to="/blog/blog-single">Blog single</NuxtLink></li>
  </ul>
</template>

<style>

</style>

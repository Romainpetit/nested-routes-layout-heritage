<template>
  <div>
    <h1>Complete Layout</h1>
    <nuxt v-if="!$slots.default" />
    <slot />
    <!-- <Nuxt /> -->
  </div>
</template>

<script>
export default {
  mounted() { console.log(this.$root.layoutName) },
};
</script>
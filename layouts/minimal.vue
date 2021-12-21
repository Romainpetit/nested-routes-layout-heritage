<template>
  <div>
    <h1>Minimal Layout</h1>
    <Nuxt />
  </div>
</template>


<script>
export default {
  mounted() { console.log(this.$slots.default) },
};
</script>

<template>
  <div>
    <h3>Parent Page</h3>
    <NuxtChild />
  </div>
</template>
 
<script>
export default {
  // layout: "complete",
  mounted() { console.log(this.$root.layoutName) },
};
</script> 
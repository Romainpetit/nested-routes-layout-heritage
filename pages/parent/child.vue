<template>
  <div>
    <h3>Child Page</h3>
    <Tutorial />
  </div>
</template>

<script>
export default {
  layout: "minimal",
  created () {
  this.$root.setLayout('minimal')
},
  mounted() { 
    console.log(this.$root.layoutName) 
    },
};
</script>
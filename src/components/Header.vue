<template>
  <header>
    <h3>{{ title }}</h3>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    title: String,
  },
};
</script>


<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 20px;
}
</style>
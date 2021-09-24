<template>
  <header>
    <h3>{{ title }}</h3>
    <Button text="Add Task" color="green" />
  </header>
</template>

<script>
import Button from "./Button";

export default {
  name: "Header",
  props: {
    title: String,
  },
  components: {
    Button,
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
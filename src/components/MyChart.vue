<template>
  <div>
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
import go from "gojs";
const $ = go.GraphObject.make;
export default {
  name: "MyChart",
  props: {
    title: String
  },
  data() {
    return {};
  },
};
</script>
<style scoped>
</style>

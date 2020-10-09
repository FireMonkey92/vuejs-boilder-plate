<template>
  <h1>Home Page{{ name }}</h1>
</template>

<script>
export default {
  name: "AppHome",
  data() {
    return {
      name: "tanesh",
    };
  },
};
</script>

<style scoped>
h1 {
  color: green;
}
</style>
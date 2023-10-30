<template>
  <div>Hello {{ value }}</div>
  <div>{{ name }}</div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World",
      name: "lwl"
    };
  }
};
</script>

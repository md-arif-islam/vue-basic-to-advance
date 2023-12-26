<template>
  <h2>Hello {{ name }}, Hero : {{ heroName }}</h2>
</template>

<script>
export default {
  name: "GreetComponent",
  props: ["name", "heroName"],
};
</script>

<style scoped></style>

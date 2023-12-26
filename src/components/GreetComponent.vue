<template>
  <div>
    <h2>Hello {{ name }}, Hero : {{ heroName }} Age : {{ age }}</h2>
    <h2>heeeeooooooooooooo</h2>
  </div>
</template>

<script>
export default {
  name: "GreetComponent",
  props: {
    name: String,
    heroName: String,
    age: Number,
  },
};
</script>

<style scoped></style>

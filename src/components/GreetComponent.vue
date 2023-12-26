<template>
  <div>
    <h2>Hello {{ name }}, Hero : {{ heroName }} Age : {{ age }}</h2>
    <h2 v-bind="$attrs">heeeeooooooooooooo</h2>
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
  inheritAttrs: false,
};
</script>

<style scoped></style>

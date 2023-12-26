<template>
  <GreetComponent name="Arif" hero-name="Batman" :age="50" />
</template>

<script>
import GreetComponent from "./components/GreetComponent.vue";

export default {
  name: "App",
  components: { GreetComponent },

  data() {
    return {
      name: "Afrina",
      heroName: "Superman",
    };
  },
};
</script>

<style>
#app {
  text-align: center;
  margin-top: 50px;
}
</style>

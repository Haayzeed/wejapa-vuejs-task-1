<template>
  <div id="app">
    <myName :name="name"></myName>
  </div>
</template>

<script>
import myName from "./components/myName.vue";

export default {
  name: "App",
  components: {
    myName
  },
  data() {
    return {
      name: "Dosunmu Afeez"
    };
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

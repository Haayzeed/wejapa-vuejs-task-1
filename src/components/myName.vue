<template>
  <div>
    <h1>Hi there, I am {{ name }}</h1>
  </div>
</template>

<script>
export default {
  props: {
    name: {
      type: String
    }
  },
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-size: 36px;
}
</style>

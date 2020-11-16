<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  name: "HeaderTitle",
  props: {
    title: String,
  },
};
</script>

<style lang="scss">
$color_1: #2c3e50;
$font_family_1: Avenir, Helvetica, Arial, sans-serif;

h1 {
  font-family: $font_family_1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $color_1;
  margin-top: 60px;
}
</style>

<template>
  <div id="app">
    <h2>{{ message }}</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "Hello world!!!",
    };
  },
  mounted() {
    const a = "aaa";
    console.log(a);
  },
};
</script>

<style lang="scss" scoped></style>

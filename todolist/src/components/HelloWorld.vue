<template>
  <div>
    <h1>Hello world</h1>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  data() {
    return { message: "hello" };
  },
};
</script>

<style scoped></style>

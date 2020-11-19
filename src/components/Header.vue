<template>
  <header class="header">
    <h1>My first App with {{ msg }}</h1>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>

<style>
.header {
  padding: 30px;
  font-size: 40px;
  text-align: center;
  background: white;
}
</style>

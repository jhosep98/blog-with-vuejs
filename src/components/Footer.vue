<template>
  <footer class="footer">
    <p>{{ msgFooter }}</p>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  props: {
    msgFooter: String,
  },
};
</script>

<style>
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}
</style>

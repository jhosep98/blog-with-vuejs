<template>
  <main class="main">
    <Section />
    <Aside />
  </main>
</template>

<script>
import Section from "./Section.vue";
import Aside from "./Aside.vue";
export default {
  name: "Main",
  components: {
    Section,
    Aside,
  },
};
</script>

<style>
.main:after {
  content: "";
  display: table;
  clear: both;
}
</style>

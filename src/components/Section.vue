<template>
  <section class="leftcolumn">
    <Card
      title="TITLE HEADING"
      titleDescription="Title description, Dec 7, 2017"
      someText="Some text.."
      paragraph="Sunt in culpa qui officia deserunt mollit anim id est laborum
        consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore
        et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
        exercitation ullamco."
    />
    <Card
      title="TITLE HEADING 2"
      titleDescription="Title description, Dec 7, 2017"
      someText="Some text.."
      paragraph="Sunt in culpa qui officia deserunt mollit anim id est laborum
        consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore
        et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
        exercitation ullamco."
    />
  </section>
</template>

<script>
import Card from "./Card.vue";
export default {
  name: "Section",
  components: {
    Card,
  },
};
</script>

<style>
.leftcolumn {
  float: left;
  width: 75%;
}

@media screen and (max-width: 800px) {
  .leftcolumn {
    width: 100%;
    padding: 0;
  }
}
</style>

<template>
  <div class="card">
    <h2>{{ title }}</h2>
    <h5>{{ titleDescription }}</h5>
    <div class="fakeimg" style="height:200px;">Image</div>
    <p>{{ someText }}</p>
    <p>
      {{ paragraph }}
    </p>
  </div>
</template>

<script>
export default {
  name: "Section",
  props: {
    title: String,
    titleDescription: String,
    someText: String,
    paragraph: String,
  },
};
</script>

<style>
.card {
  background-color: white;
  padding: 20px;
  margin-top: 20px;
}
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}
</style>

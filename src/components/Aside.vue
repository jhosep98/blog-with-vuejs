<template>
  <div class="rightcolumn">
    <div class="card">
      <h2>About Me</h2>
      <div class="fakeimg" style="height:100px;">Image</div>
      <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
    </div>
    <div class="card">
      <h3>Popular Post</h3>
      <div class="fakeimg">Image</div>
      <br />
      <div class="fakeimg">Image</div>
      <br />
      <div class="fakeimg">Image</div>
    </div>
    <div class="card">
      <h3>Follow Me</h3>
      <p>Some text..</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Aside",
};
</script>

<style>
.rightcolumn {
  float: left;
  width: 25%;
  padding-left: 20px;
}
@media screen and (max-width: 800px) {
  .rightcolumn {
    width: 100%;
    padding: 0;
  }
}
</style>

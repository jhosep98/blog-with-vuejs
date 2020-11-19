<template>
  <div>
    <Header msg="VueJS." />
    <Main />
    <Footer msgFooter="All rights reserved 2020" />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Main from "./components/Main.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}
body {
  font-family: Arial;
  padding: 20px;
  background: #f1f1f1;
}
</style>

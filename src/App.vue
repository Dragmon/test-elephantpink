<template>
  <main>
    <Header />
  </main>
</template>
<script>
import Header from "./components/Header.vue";
export default {
  name: "App",
  components: { Header }
};
</script>

<style>
html {
  font-size: 62.5%;
}
body {
  margin: 0px;
  box-sizing: border-box;
}
h1 {
  font-size: 2.5rem;
}
h2 {
  font-size: 2rem;
}
h3,
h4,
h5,
h6 {
  font-size: 1.8rem;
}
p {
  font-size: 1.6rem;
}
</style>

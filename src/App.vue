<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  height: 100vh;
}

#app{
  height: 100%;
  background-color: #303030;
}

.container {
  margin: 0 auto;
  max-width: 1200px;
}


a {
  color: black;
  text-decoration: none;
}
</style>

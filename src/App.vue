<template>
  <NavBar :logo="logo_src" :alt="app_name" />
  <router-view />
  <FooterComponent />
</template>
<script>
import NavBar from "./components/NavBar";
import FooterComponent from "./components/FooterComponent";
export default {
  components: {
    NavBar,
    FooterComponent,
  },
  data() {
    return {
      logo_src: "/img/logo.png",
      app_name: "Make Your Burguer",
    };
  },
};
</script>

<style>
* {
  font-family: Helvetica;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.main-container {
  margin: 50px;
  min-height: 61vh;
}

h1 {
  text-align: center;
  font-size: 42px;
  margin-bottom: 30px;
  color: #222;
}
</style>

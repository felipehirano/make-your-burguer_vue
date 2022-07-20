<template>
  <NavBar />
  <FooterComponent />
  <router-view />
</template>
<script>
import NavBar from "./components/NavBar";
import FooterComponent from "./components/FooterComponent";
export default {
  components: {
    NavBar,
    FooterComponent,
  },
};
</script>

<style></style>

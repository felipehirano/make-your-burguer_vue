<template>
  <BannerComponent />
  <div class="main-container">
    <h1>Monte o seu burguer:</h1>
    <BurguerForm />
  </div>
</template>

<script>
import BannerComponent from "../components/BannerComponent.vue";
import BurguerForm from "../components/BurguerForm.vue";

export default {
  name: "HomeView",
  components: {
    BannerComponent,
    BurguerForm,
  },
};
</script>

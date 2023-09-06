<template>
  <VApp>
    <VMain>
      <Home />
    </VMain>
  </VApp>
</template>

<script>
import Home from "./components/pages/Home.vue";

export default {
  name: "App",

  components: {
    Home,
  },

  data: () => ({
    //
  }),
};
</script>

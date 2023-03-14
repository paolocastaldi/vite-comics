<script>

import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppIconsContent from "./components/AppIconsContent.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  data() {
    return {
      title: "ViteComics",
    };
  },
  components: {
    AppHeader,
    AppMain,
    AppIconsContent,
    AppFooter,
  },
};
</script>

<template>
  <AppHeader />
  <AppMain products="products" />
  <AppIconsContent />
  <AppFooter />
</template>

<style lang="scss">
@use "./style.css";
</style>
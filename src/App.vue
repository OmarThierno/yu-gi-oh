<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppCard from "./components/AppCard.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  components: {
    AppHeader,
    AppMain,
    AppCard,
    AppFooter,
  },
  data() {
    return {};
  },
};
</script>

<template>
  <AppHeader />

  <AppMain />

  <AppFooter />
</template>

<style lang="scss"></style>

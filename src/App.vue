<template>
  <Header />
  <TopSection />
</template>

<script>
import Header from "./blocks/TheHeader.vue";
import TopSection from "./blocks/TopSection.vue";

export default {
  name: "App",
  components: {
    Header,
    TopSection,
  },
};
</script>

<style lang="scss">
@import "/src/assets/scss/global/reset.scss";
@import "/src/assets/scss/global/fonts.scss";
@import "/src/assets/scss/global/global.scss";
</style>

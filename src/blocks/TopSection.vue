<script>
import TheButton from "../components/TheButton.vue";
export default {
  name: "TopSection",
  components: {
    TheButton,
  },
};
</script>
<template>
  <div class="top-section container">
    <h1 class="top-section__title title">
      Test assignment for front-end developer
    </h1>
    <p class="top-section__text">
      What defines a good front-end developer is one that has skilled knowledge
      of HTML, CSS, JS with a vast understanding of User design thinking as
      they'll be building web interfaces with accessibility in mind. They should
      also be excited to learn, as the world of Front-End Development keeps
      evolving.
    </p>
    <TheButton class="top-section__btn"> Sign up </TheButton>
  </div>
</template>
<style scoped lang="scss">
.top-section {
  background-image: url("../assets/images/top-section-bg.jpg");
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 650px;
  margin-bottom: 140px;
  &__title {
    margin-bottom: 21px;
    color: #fff;
    max-width: 380px;
  }
  &__text {
    font-size: 16px;
    line-height: 26px;
    color: #fff;
    max-width: 380px;
    text-align: center;
    margin-bottom: 32px;
  }
}
</style>

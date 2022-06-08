<script>
import TheButton from "../components/TheButton.vue";
export default {
  name: "TheHeader",
  components: {
    TheButton,
  },
};
</script>
<template>
  <div class="header container">
    <div class="header__logo">
      <a href="#" class="logo">
        <img
          src="../assets/images/logo.png"
          alt="Test task logo"
          class="logo__logo"
        />
      </a>
    </div>
    <div class="header__btns">
      <TheButton class="header__btn"> Users </TheButton>
      <TheButton class="header__btn"> Sign up </TheButton>
    </div>
  </div>
</template>
<style scoped lang="scss">
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 13px;
  &__logo {
    max-width: 104px;
    height: 26px;
  }
  &__btns {
    display: flex;
    align-items: center;
  }
  &__btn:not(:last-child) {
    margin-right: 10px;
  }
}
.logo {
  display: block;
  width: 100%;
  height: 100%;
  &__img {
    object-fit: fill;
  }
}
</style>

<script>
export default {
  name: "TheUserCard",
};
</script>
<template>
  <div class="user-card">
    <div class="user-card__img-inner">
      <img src="" alt="" class="user-card__img" />
      <ul class="user-card__info">
        <li class="user-card__item user-card__item--name"></li>
        <li class="user-card__item user-card__item--position"></li>
        <li class="user-card__item">
          <a href="#" class="user-card__link user-card__link--mail"></a>
          <a href="#" class="user-card__link user-card__link--tel"></a>
        </li>
      </ul>
    </div>
  </div>
</template>
<style scoped lang="scss"></style>

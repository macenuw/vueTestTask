<script>
export default {
  name: "TheButton",
};
</script>
<template>
  <button class="button">
    <slot></slot>
  </button>
</template>
<style scoped lang="scss">
.button {
  font-family: "Nunito";
  font-weight: 400;
  padding: 4px 18px;
  font-size: 16px;
  line-height: 26px;
  text-align: center;
  min-width: 100px;
  border-radius: 80px;
  background: #f4e041;
  border: none;
  transition: 0.3s;
  cursor: pointer;
  &:hover {
    background-color: #ffe302;
  }
  &.disabled {
    background-color: #b4b4b4;
  }
}
</style>

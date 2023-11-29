<template>
  <button class="my-button">
    <slot></slot>
  </button>
</template>

<script>
export default {
  name: "my-button",
};
</script>

<style lang="scss" scoped>
.my-button {
  padding: 5px;
  border: 1px solid gainsboro;
}
</style>

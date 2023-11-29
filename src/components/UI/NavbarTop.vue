<template>
  <div class="case">
    <div class="case__left">
      <h1>Тут должно быть лого</h1>
    </div>
    <div class="case__right">
      <my-button @click="$router.push('/about')">Пошли на Абаут </my-button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.case {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: cadetblue;
  padding: 3px;
  &__left {
    margin-left: 30px;
  }
  &__right {
    margin-right: 30px;
  }
}
</style>

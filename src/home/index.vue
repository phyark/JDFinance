<template>
  <div :class="$style.home">
    <h1>Home</h1>
  </div>
</template>

<script>
export default {
  name: 'home'
}
</script>

<style lang="scss" module>
@import "../public/css/reset.scss";
.home {
  color: red;
  font-size: 20px;
}
</style>

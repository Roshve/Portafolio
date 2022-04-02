<template>
  <button class="button">
    <slot />
  </button>
</template>

<script>
export default {
  name: "PortButton",
};
</script>

<style lang="scss" scoped>
.button {
  background-color: $PRIMARY;
}
</style>
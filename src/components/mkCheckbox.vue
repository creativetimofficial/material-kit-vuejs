<template>
  <div class="checkbox">
    <label>
    <input type="checkbox" :disabled="disabled" :checked="checked" name="optionsCheckboxes">
      <slot></slot>
    </label>
  </div>
</template>

<script>
  export default {
    props: {
      checked: Boolean,
      disabled: Boolean,
    },
  }
</script>

<style lang="scss">
  @import "../assets/sass/_common.scss";
  @import "../assets/sass/_checkboxes.scss";
</style>

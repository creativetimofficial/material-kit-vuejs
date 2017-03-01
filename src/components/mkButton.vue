<template>
  <button class="btn" :type="type" :disabled="disabled" v-if="!href">
    <slot></slot>
  </button>

  <a class="btn" :href="href" :disabled="disabled" :target="target" :rel="newRel" v-else>
    <slot></slot>
  </a>
</template>

<script>
  export default {
    props: {
      href: String,
      target: String,
      rel: String,
      type: {
        type: String,
        default: 'button',
      },
      disabled: Boolean,
    },
    computed: {
      newRel() {
        if (this.target === '_blank') {
          return this.rel || 'noopener'
        }
        return this.rel
      },
    },
  }
</script>

<style lang="scss">
  @import "../assets/sass/_common.scss";
  @import "../assets/sass/_buttons.scss";
</style>

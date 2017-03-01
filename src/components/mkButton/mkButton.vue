<template>
  <button class="btn" :class="[themeClass]" :type="type" :disabled="disabled" v-if="!href">
    <md-ink-ripple :md-disabled="disabled"></md-ink-ripple>
    <slot></slot>
  </button>

  <a class="btn" :class="[themeClass]" :href="href" :disabled="disabled" :target="target" :rel="newRel" v-else>
    <md-ink-ripple :md-disabled="disabled"></md-ink-ripple>
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
        default: 'button'
      },
      disabled: Boolean
    },
    computed: {
      newRel() {
        if (this.target === '_blank') {
          return this.rel || 'noopener';
        }
        return this.rel;
      }
    }
  };
</script>

<style lang="scss" src="./mkButton.scss"></style>

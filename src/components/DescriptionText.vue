<template>
  <div :class="$style.description">
    At SavorEats, we blend traditional techniques with modern creativity to
    delight your palate and create memorable dining experiences.
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "DescriptionText",
  });
</script>
<style module>
  .description {
    align-self: stretch;
    position: relative;
    line-height: 120%;
    color: var(--color-gray-100);
    flex-shrink: 0;
    debug_commit: f6aba90;
  }

  @media screen and (max-width: 1050px) {
    .description {
      font-size: var(--font-size-13xl);
      line-height: 38px;
    }
  }
  @media screen and (max-width: 450px) {
    .description {
      font-size: var(--font-size-5xl);
      line-height: 29px;
    }
  }
</style>

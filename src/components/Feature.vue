<template>
  <div :class="$style.feature">
    <div :class="$style.deviceContainer">
      <div :class="$style.device">
        <img
          :class="$style.iphone14Starlight1"
          alt=""
          :src="iPhone14Starlight1"
        />
        <img
          :class="$style.screenContentLummi"
          alt=""
          :src="screenContentLummi"
        />
      </div>
    </div>
    <div :class="$style.feature1">
      <b :class="$style.featureTitle">{{featureTitle}}</b>
      <div :class="$style.featureDescription">{{featureDescription}}</div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Feature",
    props: {
      iPhone14Starlight1: { type: String },
      screenContentLummi: { type: String },
      featureTitle: { type: String },
      featureDescription: { type: String },
    },
  });
</script>
<style module>
  .iphone14Starlight1 {
    position: absolute;
    height: 102.8%;
    width: 104.49%;
    top: -1.35%;
    right: -2.24%;
    bottom: -1.45%;
    left: -2.24%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
    object-fit: cover;
  }
  .screenContentLummi {
    position: absolute;
    height: 90.51%;
    width: 81.12%;
    top: 4.38%;
    right: 9.14%;
    bottom: 5.11%;
    left: 9.75%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
    object-fit: cover;
    z-index: 1;
  }
  .device {
    height: 475.2px;
    flex: 1;
    position: relative;
  }
  .deviceContainer {
    width: 312px;
    margin: 0 !important;
    position: absolute;
    top: 0px;
    left: 0px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-14xl-4);
    box-sizing: border-box;
    min-width: 228.99082946777344px;
  }
  .featureTitle {
    align-self: stretch;
    position: relative;
    line-height: 140%;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .featureDescription {
    align-self: stretch;
    position: relative;
    font-size: var(--font-size-sm);
    line-height: 150%;
    color: var(--color-silver);
    display: -webkit-inline-box;
    overflow: hidden;
    text-overflow: ellipsis;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }
  .feature1 {
    width: 312px;
    margin: 0 !important;
    position: absolute;
    top: 411.2px;
    left: 0px;
    border-radius: var(--br-base);
    background-color: var(--color-darkslategray-200);
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-base);
    box-sizing: border-box;
    gap: var(--gap-5xs);
    z-index: 1;
  }
  .feature {
    height: 497.2px;
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    position: relative;
    min-width: 125px;
    text-align: left;
    font-size: var(--font-size-lg);
    color: var(--color-lavender);
    font-family: var(--font-libre-baskerville);
  }
</style>

<template>
  <div :class="$style.plan">
    <div :class="$style.heading">
      <img :class="$style.iconIcon" alt="" :src="iconIcon" />
      <b :class="$style.title">{{title}}</b>
      <div :class="$style.shortDescription">{{shortDescription}}</div>
    </div>
    <div :class="$style.price">
      <b :class="$style.b" :style="bStyle">{{prop}}</b>
      <div :class="$style.detailsContainer">
        <div :class="$style.perMonth" :style="perMonthStyle">{{perMonth}}</div>
        <div :class="$style.yearlySwitch">
          <div :class="$style.yearly" :style="yearlyStyle">{{yearly}}</div>
          <div :class="$style.switch">
            <div :class="$style.circle" />
          </div>
        </div>
      </div>
    </div>
    <div :class="$style.featureList">
      <div :class="$style.feature">
        <img
          :class="$style.checkcircleIcon"
          alt=""
          src="/checkcircle--icon.svg"
        />
        <div :class="$style.listItem">{{listItem}}</div>
      </div>
      <div :class="$style.feature1">
        <img
          :class="$style.checkcircleIcon1"
          alt=""
          src="/checkcircle--icon.svg"
        />
        <div :class="$style.listItem1">{{listItem1}}</div>
      </div>
      <div :class="$style.feature2">
        <img
          :class="$style.checkcircleIcon2"
          alt=""
          src="/checkcircle--icon.svg"
        />
        <div :class="$style.listItem2">{{listItem2}}</div>
      </div>
      <div :class="$style.feature3">
        <img
          :class="$style.checkcircleIcon3"
          alt=""
          src="/checkcircle--icon.svg"
        />
        <div :class="$style.listItem3">{{listItem3}}</div>
      </div>
    </div>
    <div :class="$style.ctaButton">
      <div :class="$style.textContainer">
        <b :class="$style.cta">Book Your Table</b>
      </div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";
  import type * as CSS from "csstype";

  export default defineComponent({
    name: "Plan",
    props: {
      iconIcon: { type: String },
      title: { type: String },
      shortDescription: { type: String },
      prop: { type: String },
      perMonth: { type: String },
      yearly: { type: String },
      listItem: { type: String },
      listItem1: { type: String },
      listItem2: { type: String },
      listItem3: { type: String },
      propMinWidth: { type: [Object, Array, String, Number, Boolean] },
      propMinWidth1: { type: [Object, Array, String, Number, Boolean] },
      propMinWidth2: { type: [Object, Array, String, Number, Boolean] },
    },
    computed: {
      bStyle(): CSS.Properties {
        return {
          minWidth: this.propMinWidth,
        };
      },
      perMonthStyle(): CSS.Properties {
        return {
          minWidth: this.propMinWidth1,
        };
      },
      yearlyStyle(): CSS.Properties {
        return {
          minWidth: this.propMinWidth2,
        };
      },
    },
  });
</script>
<style module>
  .iconIcon {
    width: 32px;
    height: 32px;
    position: relative;
  }
  .title {
    align-self: stretch;
    position: relative;
    letter-spacing: -0.02em;
    line-height: 45px;
  }
  .shortDescription {
    align-self: stretch;
    position: relative;
    font-size: var(--font-size-sm);
    line-height: 150%;
    display: -webkit-inline-box;
    overflow: hidden;
    text-overflow: ellipsis;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }
  .heading {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-9xs);
  }
  .b {
    position: relative;
    letter-spacing: -0.02em;
    line-height: 45px;
    display: inline-block;
    min-width: 74px;
    white-space: nowrap;
  }
  .perMonth {
    position: relative;
    line-height: 160%;
    display: inline-block;
    min-width: 67px;
  }
  .yearly {
    position: relative;
    line-height: 160%;
    display: inline-block;
    min-width: 49px;
  }
  .circle {
    height: 12px;
    width: 12px;
    position: relative;
    border-radius: var(--br-21xl);
    background-color: var(--color-gray-200);
    overflow: hidden;
    flex-shrink: 0;
  }
  .switch {
    height: 16px;
    width: 26px;
    border-radius: var(--br-21xl);
    background-color: var(--color-gold);
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end;
    padding: var(--padding-11xs) var(--padding-11xs) var(--padding-11xs)
      var(--padding-xs);
    box-sizing: border-box;
  }
  .yearlySwitch {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: var(--gap-5xs);
  }
  .detailsContainer {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    font-size: var(--font-size-xs);
  }
  .price {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    padding: 0px var(--padding-141xl-3) 0px 0px;
    gap: var(--gap-5xs);
  }
  .checkcircleIcon {
    height: 24px;
    width: 24px;
    position: relative;
    min-height: 24px;
  }
  .listItem {
    flex: 1;
    position: relative;
    line-height: 150%;
  }
  .feature {
    align-self: stretch;
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: var(--gap-5xs);
  }
  .checkcircleIcon1 {
    height: 24px;
    width: 24px;
    position: relative;
    min-height: 24px;
  }
  .listItem1 {
    flex: 1;
    position: relative;
    line-height: 150%;
  }
  .feature1 {
    align-self: stretch;
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: var(--gap-5xs);
  }
  .checkcircleIcon2 {
    height: 24px;
    width: 24px;
    position: relative;
    min-height: 24px;
  }
  .listItem2 {
    flex: 1;
    position: relative;
    line-height: 150%;
  }
  .feature2 {
    align-self: stretch;
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: var(--gap-5xs);
  }
  .checkcircleIcon3 {
    height: 24px;
    width: 24px;
    position: relative;
    min-height: 24px;
  }
  .listItem3 {
    flex: 1;
    position: relative;
    line-height: 150%;
  }
  .feature3 {
    align-self: stretch;
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: var(--gap-5xs);
  }
  .featureList {
    align-self: stretch;
    height: 120px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-5xs);
    font-size: var(--font-size-sm);
    color: var(--color-silver);
  }
  .cta {
    width: 123px;
    position: relative;
    line-height: 150%;
    display: flex;
    align-items: center;
    justify-content: center;
    min-width: 123px;
  }
  .textContainer {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: 0px var(--padding-9xs);
  }
  .ctaButton {
    align-self: stretch;
    border-radius: var(--br-9xs);
    background-color: var(--color-gold);
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: var(--padding-base) var(--padding-xl);
    box-sizing: border-box;
    min-width: 140px;
    text-align: center;
    font-size: var(--font-size-sm);
    color: var(--color-gray-300);
  }
  .plan {
    flex: 1;
    border-radius: var(--br-base);
    background-color: var(--color-darkslategray-200);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    padding: var(--padding-13xl) var(--padding-6xl-3) var(--padding-13xl)
      var(--padding-13xl);
    box-sizing: border-box;
    gap: var(--gap-5xl);
    min-width: 256px;
    max-width: 100%;
    text-align: left;
    font-size: var(--font-size-19xl);
    color: var(--color-lavender);
    font-family: var(--font-libre-baskerville);
  }

  @media screen and (max-width: 1050px) {
    .title {
      font-size: var(--font-size-11xl);
      line-height: 36px;
    }

    .b {
      font-size: var(--font-size-11xl);
      line-height: 36px;
    }
  }
  @media screen and (max-width: 450px) {
    .title {
      font-size: var(--font-size-4xl);
      line-height: 27px;
    }

    .b {
      font-size: var(--font-size-4xl);
      line-height: 27px;
    }

    .price {
      flex-wrap: wrap;
      padding-right: var(--padding-xl);
      box-sizing: border-box;
    }

    .plan {
      padding-top: var(--padding-2xl);
      padding-bottom: var(--padding-2xl);
      box-sizing: border-box;
    }
  }
</style>

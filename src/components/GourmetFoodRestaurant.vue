<template>
  <div :class="$style.gourmetFoodRestaurant">
    <div :class="$style.typecenteredNav">
      <div :class="$style.brand">
        <img
          :class="$style.restaurantLogo121Icon"
          alt=""
          src="/restaurantlogo12-1@2x.png"
        />
        <div :class="$style.brandname">S E A F O O D</div>
      </div>
      <div :class="$style.navLinks">
        <div :class="$style.textContainer">
          <b :class="$style.cta">Reserve Now</b>
        </div>
      </div>
      <div :class="$style.navLinks1">
        <div :class="$style.navLink">
          <b :class="$style.navLabel">Welcome</b>
        </div>
        <div :class="$style.navLink1">
          <b :class="$style.navLabel1">Our Story</b>
        </div>
        <div :class="$style.navLink2">
          <b :class="$style.navLabel2">Our Chefs</b>
        </div>
      </div>
    </div>
    <div :class="$style.typebigImageInverted">
      <img
        :class="$style.missionImageLummi"
        alt=""
        src="/mission-image--lummi@2x.png"
      />
      <div :class="$style.textContentWrapper">
        <div :class="$style.textContent">
          <b :class="$style.benefitHeading">Our Philosophy</b
          ><DescriptionText />
        </div>
      </div>
    </div>
    <div :class="$style.typemultipleMobileDevices">
      <div :class="$style.headingContainerWrapper">
        <div :class="$style.headingContainer">
          <b :class="$style.heading">Exclusive Wines</b>
          <div :class="$style.subheading">Pairings from our sommelier</div>
        </div>
      </div>
      <div :class="$style.featureGrid">
        <Feature
          iPhone14Starlight1="/iphone-14--starlight-1@2x.png"
          screenContentLummi="/screen-content--lummi@2x.png"
          featureTitle="Seasonal Menus"
          featureDescription="Fresh ingredients, dynamic flavors."
        /><Feature
          iPhone14Starlight1="/iphone-14--starlight-11@2x.png"
          screenContentLummi="/screen-content--lummi1@2x.png"
          featureTitle="Private Events"
          featureDescription="Host with us for any occasion."
        /><Feature
          iPhone14Starlight1="/iphone-14--starlight-11@2x.png"
          screenContentLummi="/screen-content--lummi2@2x.png"
          featureTitle="Culinary Mastery"
          featureDescription="Innovation in every dish served."
        />
      </div>
    </div>
    <div :class="$style.typemobileDownload">
      <div :class="$style.container">
        <div :class="$style.submenuLabel">
          <div :class="$style.copyComponent">
            <div :class="$style.searchBarInstance">
              <b :class="$style.heading1">Join Our Culinary Journey</b>
              <div :class="$style.subheading1">
                Download our app for exclusive offers.
              </div>
            </div>
            <div :class="$style.appDownloadCombo">
              <img :class="$style.appStoreIcon" alt="" src="/app-store.svg" />
              <img
                :class="$style.googlePlayIcon"
                alt=""
                src="/google-play.svg"
              />
            </div>
          </div>
        </div>
        <div :class="$style.visualComp">
          <div :class="$style.device">
            <img
              :class="$style.iphone14Starlight1"
              alt=""
              src="/iphone-14--starlight-12@2x.png"
            />
            <img
              :class="$style.screenContentLummi"
              alt=""
              src="/screen-content--lummi3@2x.png"
            />
          </div>
          <img
            :class="$style.backgroundImageLummi"
            alt=""
            src="/background-image--lummi@2x.png"
          />
        </div>
      </div>
    </div>
    <div :class="$style.property1defaultAlt">
      <div :class="$style.copyComponent1">
        <div :class="$style.headingText">
          <b :class="$style.heading2">Reservations</b>
          <div :class="$style.subheading2">
            Choose the perfect table for your exquisite dining experience.
          </div>
        </div>
      </div>
      <div :class="$style.pricePlans">
        <Plan
          iconIcon="/icon--icon.svg"
          title="Solo"
          shortDescription="Ideal for the solo gourmand"
          prop="$29"
          perMonth="per person"
          yearly="evening"
          listItem="Welcome Drink"
          listItem1="Amuse-bouche"
          listItem2="Priority Seating"
          listItem3="Sommelier Service"
        />
        <div :class="$style.plan">
          <div :class="$style.heading3">
            <img :class="$style.iconIcon" alt="" src="/icon--icon1.svg" />
            <b :class="$style.title">Duo</b>
            <div :class="$style.shortDescription">
              Designed for couples dining
            </div>
          </div>
          <div :class="$style.price">
            <div :class="$style.price1">
              <b :class="$style.plan1">$55</b>
              <b :class="$style.heading4">00</b>
            </div>
            <div :class="$style.detailsContainer">
              <div :class="$style.perMonth">per couple</div>
              <div :class="$style.yearlySwitch">
                <div :class="$style.yearly">evening</div>
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
                src="/checkcircle--icon1.svg"
              />
              <div :class="$style.listItem">Chef's Special</div>
            </div>
            <div :class="$style.feature1">
              <img
                :class="$style.checkcircleIcon1"
                alt=""
                src="/checkcircle--icon1.svg"
              />
              <div :class="$style.listItem1">Personal Waiter</div>
            </div>
            <div :class="$style.feature2">
              <img
                :class="$style.checkcircleIcon2"
                alt=""
                src="/checkcircle--icon1.svg"
              />
              <div :class="$style.listItem2">Exclusive Menus</div>
            </div>
            <div :class="$style.feature3">
              <img
                :class="$style.checkcircleIcon3"
                alt=""
                src="/checkcircle--icon1.svg"
              />
              <div :class="$style.listItem3">Valet Parking</div>
            </div>
          </div>
          <div :class="$style.ctaButton">
            <div :class="$style.textContainer1">
              <b :class="$style.cta1">Book Your Table</b>
            </div>
          </div>
          <div :class="$style.tag">
            <b :class="$style.bestDeal">Best Choice</b>
          </div>
        </div>
        <Plan
          iconIcon="/icon.svg"
          title="Group"
          shortDescription="Ideal for parties and events"
          prop="$250"
          perMonth="per event"
          yearly="experience"
          listItem="Custom Setup"
          listItem1="Dedicated Staff"
          listItem2="Event Planning"
          listItem3="Flexible Timing"
          propMinWidth="99px"
          propMinWidth1="58px"
          propMinWidth2="68px"
        />
      </div>
    </div>
    <div :class="$style.typemegaMenuInverted">
      <div :class="$style.content">
        <div :class="$style.brand1">
          <div :class="$style.brand2">
            <img :class="$style.icon" alt="" src="/icon1.svg" />
            <b :class="$style.brandname1">SavorEats</b>
          </div>
          <div :class="$style.brandname2">Taste the Exceptional</div>
        </div>
        <div :class="$style.links">
          <div :class="$style.list">
            <b :class="$style.listHeading">Company</b>
            <div :class="$style.listLinkItem">About</div>
            <div :class="$style.listLinkItem1">Careers</div>
            <div :class="$style.listLinkItem2">Newsroom</div>
          </div>
          <div :class="$style.list1">
            <b :class="$style.listHeading1">Highlights</b>
            <div :class="$style.listLinkItem3">Chef's Bio</div>
            <div :class="$style.listLinkItem4">Photo Gallery</div>
            <div :class="$style.listLinkItem5">Press Features</div>
          </div>
          <div :class="$style.list2">
            <b :class="$style.listHeading2">Social</b>
            <div :class="$style.listLinkItem6">Twitter</div>
            <div :class="$style.listLinkItem7">Instagram</div>
            <div :class="$style.listLinkItem8">Threads</div>
          </div>
          <div :class="$style.list3">
            <b :class="$style.listHeading3">Legal</b>
            <div :class="$style.listLinkItem9">Terms</div>
            <div :class="$style.listLinkItem10">Privacy</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from "vue";
  import DescriptionText from "./DescriptionText.vue";
  import Feature from "./Feature.vue";
  import Plan from "./Plan.vue";

  export default defineComponent({
    name: "GourmetFoodRestaurant",
    components: { DescriptionText, Feature, Plan },
  });
</script>
<style module>
  .restaurantLogo121Icon {
    height: 41.5px;
    width: 40px;
    position: relative;
    border-radius: 77px;
    object-fit: cover;
  }
  .brandname {
    position: relative;
    line-height: 150%;
    display: flex;
    align-items: center;
    white-space: nowrap;
    padding-left: var(--padding-xl);
    padding-right: var(--padding-xl);
  }
  .brand {
    height: 42px;
    width: 319px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: 0px var(--padding-5xs);
    box-sizing: border-box;
    gap: var(--gap-5xs);
    z-index: 0;
    font-size: var(--font-size-sm);
  }
  .cta {
    position: relative;
    line-height: 160%;
    display: inline-block;
    min-width: 83px;
    white-space: nowrap;
  }
  .textContainer {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: 0px var(--padding-9xs);
  }
  .navLinks {
    height: 48px;
    border-radius: var(--br-9xs);
    border: 1px solid var(--color-lavender);
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: var(--padding-xs) 19px;
    z-index: 1;
    text-align: center;
  }
  .navLabel {
    position: relative;
    line-height: 160%;
    display: inline-block;
    min-width: 61px;
  }
  .navLink {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    padding: 0px var(--padding-base);
  }
  .navLabel1 {
    position: relative;
    line-height: 160%;
    display: inline-block;
    min-width: 63px;
    white-space: nowrap;
  }
  .navLink1 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    padding: 0px var(--padding-base);
  }
  .navLabel2 {
    position: relative;
    line-height: 160%;
    display: inline-block;
    min-width: 66px;
    white-space: nowrap;
  }
  .navLink2 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    padding: 0px var(--padding-base);
  }
  .navLinks1 {
    height: 38px;
    margin: 0 !important;
    position: absolute;
    top: calc(50% - 18.5px);
    left: calc(50% - 168.2px);
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    padding: 0px var(--padding-base);
    box-sizing: border-box;
    gap: var(--gap-base);
    z-index: 2;
  }
  .typecenteredNav {
    align-self: stretch;
    height: 59px;
    background-color: var(--color-gray-200);
    display: none;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    padding: var(--padding-5xs);
    box-sizing: border-box;
    position: sticky;
    top: 0;
    z-index: 99;
    gap: var(--gap-xl);
    font-size: var(--font-size-xs);
  }
  .missionImageLummi {
    height: 425px;
    flex: 1;
    border-radius: 24px;
    max-width: 600px;
    overflow: hidden;
    object-fit: cover;
    min-width: 280px;
  }
  .benefitHeading {
    margin-top: -56px;
    align-self: stretch;
    position: relative;
    line-height: 120%;
    display: inline-block;
    flex-shrink: 0;
    debug_commit: f6aba90;
  }
  .textContent {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 50px 0px 284px;
    box-sizing: border-box;
    gap: var(--gap-5xs);
    min-width: 280px;
    max-width: 600px;
  }
  .textContentWrapper {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 45px 0px 0px;
    box-sizing: border-box;
    min-width: 335px;
    max-width: 100%;
  }
  .typebigImageInverted {
    align-self: stretch;
    background-color: var(--color-white);
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 80px 39.5px;
    box-sizing: border-box;
    gap: 20px 46px;
    max-width: 100%;
    z-index: 1;
    font-size: var(--font-size-21xl);
    color: var(--color-gold);
  }
  .heading {
    align-self: stretch;
    position: relative;
    letter-spacing: -0.02em;
    line-height: 120%;
  }
  .subheading {
    align-self: stretch;
    position: relative;
    font-size: var(--font-size-sm);
    line-height: 150%;
    color: var(--color-silver);
  }
  .headingContainer {
    width: 800px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 12px;
    max-width: 800px;
  }
  .headingContainerWrapper {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    max-width: 100%;
  }
  .featureGrid {
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: center;
    padding: 0px 108px;
    box-sizing: border-box;
    gap: 24px 22px;
    max-width: 1200px;
  }
  .typemultipleMobileDevices {
    align-self: stretch;
    background-color: var(--color-gray-200);
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 160px var(--padding-44xl-5);
    box-sizing: border-box;
    gap: var(--gap-21xl);
    max-width: 100%;
    text-align: center;
  }
  .heading1 {
    align-self: stretch;
    position: relative;
    letter-spacing: -0.02em;
    line-height: 120%;
    display: -webkit-inline-box;
    overflow: hidden;
    text-overflow: ellipsis;
    -webkit-line-clamp: 3;
    -webkit-box-orient: vertical;
  }
  .subheading1 {
    align-self: stretch;
    position: relative;
    font-size: var(--font-size-lg);
    line-height: 140%;
    color: var(--color-silver);
  }
  .searchBarInstance {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-base);
  }
  .appStoreIcon {
    height: 56px;
    width: 166px;
    position: relative;
    overflow: hidden;
    flex-shrink: 0;
    min-height: 56px;
  }
  .googlePlayIcon {
    height: 56px;
    width: 189px;
    position: relative;
    overflow: hidden;
    flex-shrink: 0;
    min-height: 56px;
  }
  .appDownloadCombo {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-base);
  }
  .copyComponent {
    width: 100%;
    border-radius: var(--br-base);
    background-color: var(--color-gray-200);
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 32px;
    min-width: 304px;
    max-width: 524px;
  }
  .submenuLabel {
    width: 524px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 144.5px 0px 0px;
    box-sizing: border-box;
    max-width: 100%;
  }
  .iphone14Starlight1 {
    position: absolute;
    height: 102.81%;
    width: 104.48%;
    top: -1.35%;
    right: -2.26%;
    bottom: -1.46%;
    left: -2.22%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
    object-fit: cover;
  }
  .screenContentLummi {
    position: absolute;
    height: 90.52%;
    width: 81.11%;
    top: 4.37%;
    right: 9.18%;
    bottom: 5.11%;
    left: 9.71%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
    object-fit: cover;
    z-index: 1;
  }
  .device {
    height: 100%;
    width: 279px;
    position: absolute;
    margin: 0 !important;
    top: 0px;
    bottom: 0px;
    left: 0px;
  }
  .backgroundImageLummi {
    height: 376px;
    width: 381px;
    position: absolute;
    margin: 0 !important;
    top: 82px;
    left: 247px;
    border-radius: var(--br-base);
    overflow: hidden;
    flex-shrink: 0;
    object-fit: cover;
    z-index: 2;
  }
  .visualComp {
    height: 540px;
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    position: relative;
    min-width: 420px;
    max-width: 640px;
  }
  .container {
    flex: 1;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-11xs) 0px 0px;
    box-sizing: border-box;
    gap: 48px 46px;
    max-width: 1200px;
  }
  .typemobileDownload {
    align-self: stretch;
    background-color: var(--color-gray-200);
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-85xl) var(--padding-44xl-5);
    box-sizing: border-box;
    max-width: 100%;
  }
  .heading2 {
    align-self: stretch;
    position: relative;
    letter-spacing: -0.02em;
    line-height: 120%;
    display: -webkit-inline-box;
    overflow: hidden;
    text-overflow: ellipsis;
    -webkit-line-clamp: 3;
    -webkit-box-orient: vertical;
  }
  .subheading2 {
    align-self: stretch;
    position: relative;
    font-size: 22px;
    line-height: 29px;
    color: var(--color-silver);
  }
  .headingText {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    gap: var(--gap-base);
  }
  .copyComponent1 {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-width: 304px;
    max-width: 720px;
  }
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
  .heading3 {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-9xs);
  }
  .plan1 {
    position: relative;
    letter-spacing: -0.02em;
    line-height: 45px;
    display: inline-block;
    min-width: 69px;
    white-space: nowrap;
  }
  .heading4 {
    width: 24px;
    position: relative;
    font-size: var(--font-size-lg);
    line-height: 140%;
    display: flex;
    font-family: var(--font-manrope);
    color: var(--color-lavender);
    align-items: center;
    flex-shrink: 0;
  }
  .price1 {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 3px;
  }
  .perMonth {
    position: relative;
    line-height: 160%;
    display: inline-block;
    min-width: 66px;
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
    padding: 0px 138.3px 0px 0px;
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
    color: var(--color-darkslategray-100);
  }
  .cta1 {
    width: 123px;
    position: relative;
    line-height: 150%;
    display: flex;
    align-items: center;
    justify-content: center;
    min-width: 123px;
  }
  .textContainer1 {
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
  .bestDeal {
    position: relative;
    line-height: 160%;
    display: inline-block;
    min-width: 75px;
  }
  .tag {
    margin: 0 !important;
    position: absolute;
    top: 16px;
    right: 11px;
    border-radius: 8px;
    background-color: var(--color-gold);
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: var(--padding-5xs);
    white-space: nowrap;
    z-index: 1;
    font-size: var(--font-size-xs);
    color: var(--color-gray-300);
  }
  .plan {
    flex: 1;
    border-radius: var(--br-base);
    background-color: var(--color-white);
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    padding: var(--padding-base) 24px 40px var(--padding-13xl);
    box-sizing: border-box;
    position: relative;
    gap: var(--gap-5xl);
    min-width: 256px;
    min-height: 476px;
    max-width: 100%;
  }
  .pricePlans {
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    gap: 16px 14px;
    max-width: 1200px;
    text-align: left;
    font-size: var(--font-size-19xl);
    color: var(--color-gray-100);
  }
  .property1defaultAlt {
    align-self: stretch;
    background-color: var(--color-gray-200);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 120px var(--padding-44xl-5);
    box-sizing: border-box;
    gap: var(--gap-21xl);
    max-width: 100%;
    text-align: center;
  }
  .icon {
    height: 32px;
    width: 32px;
    position: relative;
  }
  .brandname1 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 72px;
  }
  .brand2 {
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    gap: var(--gap-5xs);
  }
  .brandname2 {
    position: relative;
    font-size: var(--font-size-lg);
    line-height: 140%;
  }
  .brand1 {
    height: 81px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 403px 0px 0px;
    box-sizing: border-box;
    gap: var(--gap-5xl);
    min-width: 248px;
    max-width: 100%;
  }
  .listHeading {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 73px;
  }
  .listLinkItem {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 44px;
  }
  .listLinkItem1 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 55px;
  }
  .listLinkItem2 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 79px;
  }
  .list {
    flex: 0.7745;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 41px 0px 0px;
    box-sizing: border-box;
    gap: var(--gap-base);
    min-width: 108px;
  }
  .listHeading1 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 78px;
  }
  .listLinkItem3 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 74px;
  }
  .listLinkItem4 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 100px;
  }
  .listLinkItem5 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 102px;
  }
  .list1 {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 18px 0px 0px;
    box-sizing: border-box;
    gap: var(--gap-base);
    min-width: 108px;
  }
  .listHeading2 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 45px;
  }
  .listLinkItem6 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 53px;
  }
  .listLinkItem7 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 73px;
  }
  .listLinkItem8 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 59px;
  }
  .list2 {
    flex: 0.7157;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 47px 0px 0px;
    box-sizing: border-box;
    gap: var(--gap-base);
    min-width: 108px;
  }
  .listHeading3 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 41px;
  }
  .listLinkItem9 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 46px;
  }
  .listLinkItem10 {
    position: relative;
    line-height: 150%;
    display: inline-block;
    min-width: 54px;
  }
  .list3 {
    flex: 0.5294;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 66px 0px 0px;
    box-sizing: border-box;
    gap: var(--gap-base);
    min-width: 108px;
  }
  .links {
    width: 600px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px 0px 0px var(--padding-9xs);
    box-sizing: border-box;
    gap: 40px 38.7px;
    min-width: 280px;
    max-width: 100%;
  }
  .content {
    flex: 1;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: space-between;
    max-width: 1200px;
    gap: -2px;
  }
  .typemegaMenuInverted {
    align-self: stretch;
    background-color: var(--color-white);
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    padding: 64px var(--padding-44xl-5);
    box-sizing: border-box;
    max-width: 100%;
    font-size: var(--font-size-sm);
    color: var(--color-gray-100);
  }
  .gourmetFoodRestaurant {
    width: 1327px;
    background-color: var(--color-white);
    max-width: 100%;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    letter-spacing: normal;
    text-align: left;
    font-size: var(--font-size-32xl);
    color: var(--color-lavender);
    font-family: var(--font-libre-baskerville);
  }

  @media screen and (max-width: 1200px) {
    .featureGrid {
      padding-left: var(--padding-35xl);
      padding-right: var(--padding-35xl);
      box-sizing: border-box;
      max-width: 100%;
    }

    .container {
      max-width: 100%;
    }

    .pricePlans {
      max-width: 100%;
    }

    .content {
      max-width: 100%;
    }
  }
  @media screen and (max-width: 1050px) {
    .benefitHeading {
      font-size: var(--font-size-13xl);
      line-height: 38px;
    }

    .heading {
      font-size: var(--font-size-22xl);
      line-height: 49px;
    }

    .headingContainer {
      max-width: 100%;
    }

    .typemultipleMobileDevices {
      padding-top: var(--padding-85xl);
      padding-bottom: var(--padding-85xl);
      box-sizing: border-box;
    }

    .heading1 {
      font-size: var(--font-size-22xl);
      line-height: 49px;
    }

    .heading2 {
      font-size: var(--font-size-22xl);
      line-height: 49px;
    }

    .title {
      font-size: var(--font-size-11xl);
      line-height: 36px;
    }

    .plan1 {
      font-size: var(--font-size-11xl);
      line-height: 36px;
    }

    .property1defaultAlt {
      padding-top: var(--padding-59xl);
      padding-bottom: var(--padding-59xl);
      box-sizing: border-box;
    }
  }
  @media screen and (max-width: 750px) {
    .missionImageLummi {
      max-width: 100%;
    }

    .textContent {
      padding-top: var(--padding-13xl);
      padding-bottom: 185px;
      box-sizing: border-box;
      max-width: 100%;
    }

    .typebigImageInverted {
      gap: 20px 23px;
      padding-top: var(--padding-33xl);
      padding-bottom: var(--padding-33xl);
      box-sizing: border-box;
    }

    .featureGrid {
      padding-left: var(--padding-8xl);
      padding-right: var(--padding-8xl);
      box-sizing: border-box;
    }

    .typemultipleMobileDevices {
      gap: 20px 40px;
      padding: var(--padding-49xl) var(--padding-12xl);
      box-sizing: border-box;
    }

    .copyComponent {
      gap: 16px 32px;
      max-width: 100%;
    }

    .visualComp {
      max-width: 100%;
    }

    .container {
      gap: 48px 23px;
    }

    .typemobileDownload {
      gap: 48px 24px;
      padding: var(--padding-49xl) var(--padding-12xl);
      box-sizing: border-box;
    }

    .copyComponent1 {
      gap: 20px 40px;
      max-width: 100%;
    }

    .property1defaultAlt {
      gap: 20px 40px;
      padding-left: var(--padding-12xl);
      padding-right: var(--padding-12xl);
      box-sizing: border-box;
    }

    .brand1 {
      padding-right: 201px;
      box-sizing: border-box;
    }

    .links {
      gap: 40px 19px;
    }

    .typemegaMenuInverted {
      padding-left: var(--padding-12xl);
      padding-right: var(--padding-12xl);
      box-sizing: border-box;
    }
  }
  @media screen and (max-width: 450px) {
    .benefitHeading {
      font-size: var(--font-size-5xl);
      line-height: 29px;
    }

    .textContentWrapper {
      padding-top: 29px;
      box-sizing: border-box;
    }

    .heading {
      font-size: var(--font-size-12xl);
      line-height: 37px;
    }

    .heading1 {
      font-size: var(--font-size-12xl);
      line-height: 37px;
    }

    .submenuLabel {
      padding-top: 94px;
      box-sizing: border-box;
    }

    .heading2 {
      font-size: var(--font-size-12xl);
      line-height: 37px;
    }

    .subheading2 {
      font-size: var(--font-size-lg);
      line-height: 23px;
    }

    .title {
      font-size: var(--font-size-4xl);
      line-height: 27px;
    }

    .plan1 {
      font-size: var(--font-size-4xl);
      line-height: 27px;
    }

    .price {
      flex-wrap: wrap;
      padding-right: var(--padding-xl);
      box-sizing: border-box;
    }

    .plan {
      padding-top: var(--padding-xl);
      padding-bottom: 26px;
      box-sizing: border-box;
    }

    .property1defaultAlt {
      padding-top: var(--padding-32xl);
      padding-bottom: var(--padding-32xl);
      box-sizing: border-box;
    }

    .brand1 {
      padding-right: var(--padding-xl);
      box-sizing: border-box;
    }
  }
</style>

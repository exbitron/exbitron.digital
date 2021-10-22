<template>
  <main class="ui-wrapper page-not-loaded">
    <!-- LOADER -->
    <div class="loader flex flex--center">
      <span class="loader__text">EXTO</span>
    </div>

    <MainMenu></MainMenu>

    <Header></Header>

    <RightPagin></RightPagin>

    <Footer></Footer>

    <!-- MAIN CONTENT -->
    <div class="content">
      <ScrollElement></ScrollElement>

      <AboutUs></AboutUs>

      <Offer></Offer>

      <Team></Team>

      <HowToGetToken></HowToGetToken>

      <ContactUs></ContactUs>
    </div>
  </main>
</template>

<script lang="ts">
import Vue from "vue";
import MainMenu from "~/components/MainMenu.vue";
import RightPagin from "~/components/RightPagin.vue";
import Popup from "~/components/Popup.vue";
import Footer from "~/components/Footer.vue";
import ScrollElement from "~/components/ScrollElement.vue";
import AboutUs from "~/components/AboutUs.vue";
import Offer from "~/components/Offer.vue";
import Team from "~/components/Team.vue";
import HowToGetToken from "~/components/HowToGetToken.vue";
import ContactUs from "~/components/ContactUs.vue";

export default Vue.extend({});
</script>

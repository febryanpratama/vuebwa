<template>
  <div class="home">
    <HeaderShayna />
    <HeroCarousel />
    <BannerCarousel />
    <InstaShayna />
    <LogoPartner />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";\
// import carousel from "vue-owl-carousel";
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroCarousel from "@/components/HeroCarousel.vue";
import BannerCarousel from "@/components/BannerCarousel.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import LogoPartner from "@/components/LogoPartner.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld,
    HeaderShayna,
    // carousel,
    HeroCarousel,
    BannerCarousel,
    InstaShayna,
    LogoPartner,
    FooterShayna,
  },
};
</script>

<template>
  <div class="home">
    <HeaderSalwa/>
    <HeroSalwa/>
    <BannerWomanSalwa/>
    <InstagramPhotoSalwa/>
    <PartnerSalwa/>
    <FooterSalwa/>
  </div>
</template>

<script>

// import carousel from 'vue-owl-carousel'
import HeaderSalwa from '@/components/HeaderSalwa.vue'
import HeroSalwa from '@/components/HeroSalwa.vue'
import BannerWomanSalwa from '@/components/BannerWomanSalwa'
import InstagramPhotoSalwa from '@/components/InstagramPhotoSalwa'
import FooterSalwa from '@/components/FooterSalwa'
import PartnerSalwa from '@/components/PartnerSalwa'

export default {
  name: 'Home',
  components: {
    HeaderSalwa,
    HeroSalwa,
    BannerWomanSalwa,
    InstagramPhotoSalwa,
    PartnerSalwa,
    FooterSalwa
  }
}
</script>

  
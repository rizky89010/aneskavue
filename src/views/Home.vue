<template>
  <div class="home">
    <HeaderAneska />
    <carouselaneska />
    <carouselbawah />
    <instaaneska />
    <partnerlogo />
    <footeraneska/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderAneska from '@/components/HeaderAneska.vue';
import carouselaneska from '@/components/carouselaneska.vue';
import carouselbawah from '@/components/carouselbawah.vue';
import instaaneska from '@/components/instaaneska.vue';
import partnerlogo from '@/components/partnerlogo.vue';
import footeraneska from '@/components/footeraneska.vue';


export default {
  name: 'Home',
  components: {
    HeaderAneska,
    carouselaneska,
    carouselbawah,
    instaaneska,
    partnerlogo,
    footeraneska,
  }
}
</script>

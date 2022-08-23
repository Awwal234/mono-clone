<template>
  <main>
    <HeaderPage/>
    <HeroSection/>
    <BuildFuture/>
  </main>
</template>

<script>
import HeaderPage from "@/components/HeaderPage.vue";
import HeroSection from '@/components/HeroSection.vue';
import BuildFuture from "@/components/BuildFuture.vue";
export default {
  components: {
    HeaderPage,
    HeroSection,
    BuildFuture,
},
}
</script>
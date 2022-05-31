<template>
  <div>
    <HeaderLayout />
    <AboutCont />
    <FooterLayout />
  </div>
</template>

<script>
import HeaderLayout from "@/components/HeaderLayout.vue";
import AboutCont from "@/components/AboutCont.vue";
import FooterLayout from "@/components/FooterLayout.vue";

export default {
  components: {
    HeaderLayout,
    AboutCont,
    FooterLayout,
  },
};
</script>

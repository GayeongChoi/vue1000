<template>
  <div>
    <HeaderLayout />
    <MainCont />
    <FooterLayout />
  </div>
</template>

<script>
import HeaderLayout from "@/components/HeaderLayout.vue";
import MainCont from "@/components/MainCont.vue";
import FooterLayout from "@/components/FooterLayout.vue";
export default {
  components: {
    HeaderLayout,
    MainCont,
    FooterLayout,
  },
};
</script>

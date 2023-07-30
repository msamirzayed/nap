<template>
  <SectionOne />
  <!-- section 2 -->
  <SectionTwo />
  <!-- section 3 -->
  <SectionThree />
  <!-- section 4 -->
  <SectionFour />
</template>

<script>
import SectionOne from "./SectionOne.vue";
import SectionThree from "./SectionThree.vue";
import SectionTwo from "./SectionTwo.vue";
import SectionFour from "./SectionFour.vue";

export default {
  name: "HomeView",
  components: { SectionOne, SectionTwo, SectionThree, SectionFour },
};
</script>

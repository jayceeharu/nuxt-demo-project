<template>
  <div class=".container-fluid">
    <Header />
    <RealEstate
      v-for="hotelInfo in realEstateInfo"
      :key="hotelInfo.id"
      :realEstateSection="hotelInfo"
    />
  </div>
</template>

<script>
import { realEstateData } from "@/assets/data.js";
export default {
  data() {
    return {
      realEstateInfo: realEstateData,
    };
  },
};
</script>

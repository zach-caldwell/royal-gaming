<template>
  <div>
    <HomeBanner/>
    <WhyUs/>
    <MostPlayedGames/>
  </div>
</template>

<script>
import HomeBanner from "../components/HomeBanner";
import WhyUs from "../components/WhyUs";
import MostPlayedGames from "../components/MostPlayedGames";

export default {
  components: {
    HomeBanner,
    WhyUs,
    MostPlayedGames
  }
};
</script>
